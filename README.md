# 🌍 Air Quality UCI - Data Preprocessing and Analysis

## 📌 Project Overview
This project focuses on cleaning, transforming, and exploring the Air Quality UCI dataset. The data was collected from March 2004 to February 2005, capturing hourly readings of pollutants and weather conditions from an Italian city.

## 📊 Dataset Information
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Air+Quality)
- Total Records: 9,358 rows
- Features: 15 attributes including CO, NOx, NMHC, Benzene, Temperature, and Humidity

## 📂 Dataset

The dataset used in this project is based on the [UCI Air Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Air+Quality).

➡️ You can download the dataset file directly from this repository:  
[Download AirQualityUCI.xlsx](./AirQualityUCI.xlsx)


## 🧹 Preprocessing Steps
- Replaced invalid readings (like -200) with NaN
- Combined Date and Time into a single DateTime column
- Handled missing values using forward fill and mean imputation
- Dropped unnecessary or empty columns
- Converted columns to proper data types

## 📈 Exploratory Data Analysis (EDA)
- Plotted pollutant levels over time
- Used histograms and box plots to understand distribution
- Created correlation heatmaps to identify feature relationships
- Checked seasonal patterns in CO and NOx levels

## 🧰 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook / Google Colab

## 🚀 How to Use
1. Clone this repository
2. Open the notebook `air_quality_analysis.ipynb`
3. Run all cells to view preprocessing and visualizations

## ✅ Results
- Clean dataset ready for ML models
- Visual insights into pollution behavior
- Baseline understanding for future forecasting

## 🙏 Acknowledgements
- Dataset: UCI ML Repository
- Author: Shaharshan Muhammed Shakkir
