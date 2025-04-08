# 🌍 Climate Trends Prediction Using Machine Learning

## 🔗 Project Notebook Viewer
Due to GitHub’s file size limitations on displaying large `.ipynb` notebooks, the final project presentation is hosted via [NBViewer](https://nbviewer.org), which ensures full rendering and interactivity:

👉 **View the full notebook here:**  
https://nbviewer.org/github/ShaiShillo/climate-trends-prediction/blob/master/.ipynb_checkpoints/Final_project_presentation_one_pager-checkpoint.ipynb

---

## 📌 Overview
This project uses historical climate data to **predict future global temperature trends** using machine learning algorithms. By analyzing temperature records from 2015 to 2023, it demonstrates how ML can help us understand and prepare for climate change impacts.

---

## 📚 Table of Contents
- [Introduction](#introduction)
- [Data Source](#data-source)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [Authors](#authors)

---

## 🔎 Introduction
Climate change is a global challenge that affects both natural and human systems. This project aims to leverage machine learning to forecast future temperature trends by identifying patterns in historical weather data. Algorithms like **Linear Regression**, **Random Forest**, and **Polynomial Regression** were used to explore and model this data.

---

## 📊 Data Source
- **Source**: [Weather Underground](https://www.wunderground.com/)  
- **Period Covered**: 2015–2023  
- **Number of Samples**: 102,655  
- **Features Included**:
  - `Year`, `Month`, `Day`, `Temperature`, `Temp Dew Point`, `Humidity`
  - `Wind Direction`, `Wind Speed`, `Precipitation`, `Condition`
  - `Location`, `Serialized Hemisphere`

### 🧹 Preprocessing Steps:
1. **Data Cleaning** – Removed or imputed missing values and filtered outliers.
2. **Feature Engineering** – Created new features like `season` from month.
3. **Scaling** – Applied `StandardScaler` or `MinMaxScaler` to numeric data.
4. **Encoding** – Used one-hot encoding for categorical variables.
5. **Train-Test Split** – Data split into 80% training and 20% testing.
6. **Feature Selection** – Applied variance threshold and correlation/p-value analysis.
7. **Missing Value Imputation** – Used KNN imputer for remaining missing entries.

---

## 🧠 Methodology
We implemented and compared several ML models:
- **Linear Regression**
- **Random Forest Regression**
- **Polynomial Regression**

### 📏 Evaluation Metrics:
- **R² Score**
- **Mean Squared Error (MSE)**

---

## 💻 Installation
To install the necessary dependencies:

```bash
pip install -r requirements.txt
