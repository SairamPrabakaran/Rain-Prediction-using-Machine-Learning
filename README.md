# Rain Prediction in Australia using Machine Learning  
**Tools Used:** Python, Keras (LSTM), Pandas, NumPy, Seaborn, Plotly

---

## 📌 Project Overview

This project aims to forecast whether it will rain tomorrow in Australia using a dataset that includes four years of daily weather measurements across various regions. By applying data preprocessing, exploratory data analysis (EDA), and machine learning techniques — including an LSTM-based neural network — the model predicts rainfall likelihood with the goal of supporting weather-related decisions and planning.

---

## 🔧 Tools & Technologies

- **Programming Language:** Python  
- **Libraries & Frameworks:**  
  - Data Manipulation: Pandas, NumPy  
  - Visualization: Seaborn, Matplotlib, Plotly  
  - Preprocessing: Scikit-learn, LabelEncoder, StandardScaler  
  - Deep Learning: Keras (LSTM), TensorFlow  
  - Evaluation: Accuracy, F1-score, Precision, Recall, Confusion Matrix

---

## 📂 Dataset

- **Source:** [Kaggle Weather Dataset – Australia](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)
- **Rows:** ~62,000  
- **Columns:** 30  
- **Target Variable:** `RainTomorrow` (Yes/No)

Each row represents weather observations from various locations in Australia, including features such as:
- Date, Location, Temperature (Min/Max), Humidity, Wind, Sunshine, Pressure, Cloud cover, etc.

---

## 📈 Exploratory Data Analysis (EDA)

Key insights and steps during EDA include:
- Handling missing values using conditional logic and interpolation
- Creating new time-based features (`day`, `month`, `month_sin`, `month_cos`)
- Visualizing relationships between rainfall and temperature, humidity, and wind
- Using Plotly for interactive visualizations

---

## 🧠 Model Building

A deep learning model using **LSTM (Long Short-Term Memory)** was developed to capture temporal patterns in the weather data.

### Steps:
- Label encoding categorical variables
- Standard scaling for numerical features
- Splitting data into train/test sets
- Creating LSTM model with dropout, batch normalization, and dense layers
- Compiling with **Adam optimizer** and evaluating using accuracy and F1-score

---

## 🧪 Evaluation Metrics

The model performance was evaluated using:

- ✅ **Accuracy Score**
- ✅ **F1 Score**
- ✅ **Precision & Recall**
- ✅ **Confusion Matrix**
- ✅ **Classification Report**

---

## 📊 Visualizations

- Feature distributions and correlations using **Seaborn**
- Time series plots for trends and seasonality
- Confusion matrix and model metrics plots
- Interactive dashboards using **Plotly**
