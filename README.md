# 📊 AltSchool Data Science Project: Tinyuka 2024 Second Semester

This project is submitted as part of the AltSchool of Data Science **Tinyuka 2024 Second Semester Assessment**. It focuses on analyzing a real-world housing dataset and COVID-19 case data to demonstrate handling missing values, aggregating data, and performing basic time series analysis.

---

## 📁 Project Structure

```
.
├── Akintomiwa_Akinpelu.ipynb     # Main Jupyter Notebook with all analysis
├── house_prices.csv              # Housing dataset (used for Task 1)
└── README.md                     # Project documentation
```

---

## ✅ Assessment Tasks Completed

### 1. 🧹 Dealing with Missing Data

- Categorized missing values in `house_prices.csv` as **MAR**, **MCAR**, or **MNAR**
- Justified each classification using observed patterns (e.g., plot types missing `size`, etc.)
- Found that:
  - `size`, `bath`, `balcony`, and `society` = **MAR**
  - `location` = **MCAR**

---

### 2. 📊 Data Aggregation and Grouping

- Loaded the **NYT COVID-19 Dataset** for U.S. counties in 2020.
- Aggregated **average COVID-19 cases by county** (or state).
- Rounded results to 2 decimal places for clean presentation.
- Displayed top 10 and bottom 5 counties for insights.

---

### 3. ⏱️ Time Series Analysis

- Converted the `date` column to `datetime` format.
- Extracted short-form month names (e.g., Jan, Feb) and converted to categorical for ordering.
- Filtered data for **California**.
- Generated a **line plot** showing **monthly total COVID-19 cases** for the state.

---

## 📈 Libraries Used

- `pandas`
- `matplotlib`
- `seaborn` (optional)

---

## 📌 Dataset Sources

- **House Prices Dataset** (provided by AltSchool)
- **NYT COVID-19 Data**  
  🔗 [us-counties-2020.csv](https://raw.githubusercontent.com/nytimes/covid-19-data/master/us-counties-2020.csv)

---

## 🧠 Author

- **Akintomiwa Akinpelu**
- AltSchool of Data Science – Tinyuka Track
- 2024 Second Semester Project

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Install dependencies:
   ```bash
   pip install pandas matplotlib
   ```

3. Open the notebook:
   ```bash
   jupyter notebook Akintomiwa_Akinpelu.ipynb
   ```

---

## 📬 Feedback

Feel free to open an issue or submit a pull request if you'd like to improve the project!
