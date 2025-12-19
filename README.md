# 🌍 Global COVID-19 Data Analysis (Python)

A beginner-to-intermediate **Python data analysis and visualization project** using real-world COVID-19 time-series data from the **Johns Hopkins University CSSE** repository.

---

## 📌 Project Overview

* **Language:** Python
* **Domain:** Data Analysis & Visualization
* **Dataset:** Global COVID-19 Confirmed Cases (Time Series)

This project analyzes the spread of COVID-19 across countries and visualizes global trends using Python libraries.

---

## 📂 Dataset Source

The dataset is directly fetched from the official GitHub repository:

```
https://github.com/CSSEGISandData/COVID-19
```

---

## 🛠️ Libraries Used

* **Pandas** – Data loading, cleaning, and aggregation
* **Matplotlib** – Line plots and basic visualizations
* **Seaborn** – Enhanced plot styling

---

## 🔄 Data Processing Workflow

1. Load the COVID-19 confirmed cases dataset using Pandas
2. Group data by **Country/Region**
3. Aggregate confirmed cases for each country
4. Transpose the dataset so that dates become the index
5. Convert date index to DateTime format
6. Remove invalid or missing date values
7. Compute global and country-wise totals

---

## 📈 Visualizations Generated

### 1️⃣ Global COVID-19 Cases Over Time

* Line plot showing worldwide confirmed cases growth over time

### 2️⃣ Top 5 Most Affected Countries

* Bar chart displaying the countries with the highest total confirmed cases

### 3️⃣ Country-wise Comparison

* Line plot comparing COVID-19 trends for:

  * United States
  * India
  * Brazil

### 4️⃣ Distribution of Cases (Top 5 Countries)

* Pie chart showing the percentage distribution of cases

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
```

### Step 2: Install Required Libraries

```bash
pip install pandas matplotlib seaborn
```

### Step 3: Run the Python Script

```bash
python covid_analysis.py
```

---

## 📁 Project Structure

```
covid-19-python-analysis/
│
├── covid_analysis.py
└── README.md
```

---

## 🎯 Key Learning Outcomes

* Handling real-world time-series data using Python
* Data aggregation and transformation with Pandas
* Creating clean visualizations with Matplotlib and Seaborn
* Understanding global pandemic trends through data

---

## 🙏 Acknowledgements

* **Johns Hopkins University – CSSE**
* Open-source Python community

---

## ⭐ Conclusion

This project demonstrates a **simple yet effective Python data analysis workflow** and is ideal for students learning data analytics and visualization.

---
