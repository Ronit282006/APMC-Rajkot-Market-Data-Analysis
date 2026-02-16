# 📊 APMC Rajkot Market Data Analysis

## 📌 Project Overview
This project analyzes APMC Rajkot market data to understand commodity pricing behavior, supply trends, price volatility, and the relationship between arrival quantity and price.

The analysis was performed using Python in Jupyter Notebook and focuses on extracting actionable insights from market rate datasets.

---

## 📂 Files Included

- analysis_report.pdf – Detailed analysis report
- apmc_rajkot.csv – Raw market dataset
- apmc_rajkot_rates.csv – Rates dataset
- apmc.ipynb – Jupyter Notebook containing code and outputs

---

## 🛠 Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn (MinMaxScaler)
- Jupyter Notebook

---

## 🔎 Key Analysis Performed

### 1️⃣ Commodity Pricing Analysis
Identified highest and lowest average rate commodities based on normalized pricing data.

**Top 5 Most Expensive Commodities:**
- Rajkoo Bee
- Sesmum-Black (Black Sesame)
- Cummin (Jeera)
- Kalonji
- Seasmum (Sesame)

**Top 5 Least Expensive Commodities:**
- Cabbage
- Papaya
- Green Corn
- Onion
- Water Melon

---

### 2️⃣ Price Volatility Analysis
Measured standard deviation of commodity prices to determine risk and fluctuation levels.

Highest volatility observed in:
- Rajkoo Bee
- Green Garlic
- Chillies
- Lemon
- Choli Shing

---

### 3️⃣ Supply vs Price Relationship
Performed correlation analysis between arrival quantity and average price.

- Correlation Coefficient: **-0.023**
- Conclusion: Negligible negative correlation
- Interpretation: Price movements are influenced more by seasonality, quality, and market demand rather than immediate arrival volume.

---

### 4️⃣ Seasonal Trends
Analyzed monthly average price movements.

- Peak rates observed around January
- Slight dip around May
- Prices fluctuate moderately across the year

---

## ⚙️ Methodology

- Converted date columns to datetime format
- Calculated Average Rate = (lowrate + highrate) / 2
- Applied MinMaxScaler normalization (0–1 range)
- Used groupby operations for monthly aggregation
- Generated visualizations for trend and volatility analysis

---

## 📈 Project Outcome

This project demonstrates:
- Data cleaning and preprocessing
- Feature engineering
- Statistical analysis
- Correlation analysis
- Data visualization
- Market trend interpretation

---

## 🚀 Author
APMC Data Analysis Project – 2026
