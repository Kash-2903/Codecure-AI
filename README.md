# 🌍 AI Epidemic Forecasting Dashboard

## 📌 Project Overview

AI Epidemic Forecasting Dashboard is an interactive data analytics and forecasting system developed to monitor, analyze, and predict the spread of infectious diseases such as COVID-19. The project integrates epidemiological datasets, vaccination statistics, and geographical data to provide meaningful insights through visual dashboards.

The system enables users to explore global and country-level trends, compare multiple countries, visualize outbreak severity, and generate short-term forecasts using data-driven techniques.

---

# 🎯 Objectives

* Analyze global and country-wise COVID-19 trends.
* Visualize outbreak patterns using interactive charts and maps.
* Compare pandemic statistics across different countries.
* Forecast future case trends for selected countries.
* Identify regions with different risk levels.
* Support data-driven epidemic monitoring and decision-making.

---

# 🧠 Features

## 🌍 Global Overview

* Total global cases and deaths statistics
* Global outbreak visualization using choropleth maps
* Worldwide case trend analysis

## 🏳️ Country Analysis

* Country-specific historical case trends
* Vaccination statistics visualization
* Interactive time-series charts

## 📊 Country Comparison Dashboard

* Side-by-side comparison of two countries
* Total cases comparison
* Total deaths comparison
* Vaccination rate comparison
* Trend comparison visualizations

## 🔮 Prediction Dashboard

* Forecasts next 14 days of cases
* Actual vs predicted case visualization
* Interactive prediction charts

## 🚨 Risk Map

* Global risk classification
* High, Medium, and Low risk regions
* Geographic outbreak visualization

---

# 🛠️ Tech Stack

### Programming Language

* Python

### Data Processing & Analysis

* Pandas
* NumPy

### Data Visualization

* Plotly
* Matplotlib

### Dashboard Development

* Streamlit

### Machine Learning

* Scikit-learn

---

# 📂 Project Structure

```text
CODECURE-AI_FINAL/
│
├── dashboard/
│   └── app.py
│
├── data_processed/
│   ├── final_covid_dataset.csv
│   └── feature_engineered_dataset.csv
│
├── data_raw/
│
├── notebooks/
│   └── data_preprocessing.ipynb
│
├── script/
│
├── check_data.py
├── data_pipeline.py
├── requirements.txt
├── README.md
└── run_demo.sh
```

---

# 📊 Datasets Used

### 1. Johns Hopkins COVID-19 Dataset

Provides global confirmed cases and deaths data.

### 2. Our World in Data (OWID)

Provides vaccination statistics and epidemiological indicators.

### 3. Google Mobility Reports

Used for exploratory mobility analysis and future enhancement studies.

---

# ⚙️ Installation & Setup

## Create Virtual Environment

```bash
python -m venv venv
```

## Activate Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

## Install Required Packages

```bash
pip install -r requirements.txt
```

---

# ▶️ Running the Project

## Step 1: Process the Data

```bash
python data_pipeline.py
```

## Step 2: Launch the Dashboard

```bash
streamlit run dashboard/app.py
```

---

# 📈 Dashboard Outputs

The dashboard provides:

* Global COVID-19 statistics
* Country-wise trend analysis
* Country comparison reports
* Vaccination insights
* Short-term epidemic forecasts
* Global risk classification maps

---

# 📋 Workflow

1. Collect raw epidemiological datasets.
2. Clean and preprocess the data.
3. Perform feature engineering.
4. Generate processed datasets.
5. Visualize trends through the Streamlit dashboard.
6. Produce short-term forecasts and risk assessments.

---

# 🚀 Future Enhancements

* Real-time data integration
* Multi-disease epidemic monitoring
* Advanced forecasting models
* Enhanced mobility-based analytics
* Cloud deployment
* Automated outbreak alert generation
* Regional and state-level analysis

---

# 🎓 Academic Purpose

This project was developed as part of an academic study on epidemic forecasting, data analytics, data visualization, and dashboard development using Python and Streamlit.

---

# 📜 License

This project is intended solely for educational and academic purposes.
