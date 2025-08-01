<div id="top"></div>

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![forthebadge made-with-html](https://ForTheBadge.com/images/badges/made-with-html.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML)

<h3 align="center">New York Taxi Fare Prediction</h3>

  <p align="center">
    A machine learning and web-based project to predict taxi fares in New York City using historical ride data.
    <br />
    <a href="https://github.com/Kusuma71/NewYorkTaxiFarePrediction"><strong>View Repository »</strong></a>
  </p>

---

## 🧠 Project Overview

This project was created by <b>S. Kusuma</b> as part of an internship project that combines machine learning with frontend development. The goal was to predict NYC taxi fares using ride data and present the model via a simple and interactive HTML user interface.

---

## 📌 About the Project

In this project, we used the **New York City Taxi Fare** dataset to build a machine learning model that predicts the **fare price for the next trip** based on trip features.  
The dataset can be downloaded from Kaggle:  
🔗 [NYC Taxi Dataset](https://www.kaggle.com/kentonnlp/2014-new-york-city-taxi-trips)

This dataset contains **8 key features**, including the **pickup and dropoff GPS coordinates** that allow us to compute the distance and analyze the fare behavior.

---

## 📊 Dataset Features

- `pickup_latitude`  
- `pickup_longitude`  
- `dropoff_latitude`  
- `dropoff_longitude`  
- `fare_amount`  
- `pickup_datetime`  
- `passenger_count`  

---

## 🔧 Techniques Used

- Feature Engineering  
- Data Visualization  
- Data Preprocessing  
- Machine Learning Modeling  

---

## 🤖 Algorithms Used

- Linear Regression  
- Polynomial Regression  
- Ridge Regression  
- Decision Tree Regression  
- K-Nearest Neighbors Regressor  
- Support Vector Machines  
- Neural Network  
- XGBoost  

---

## 🧰 Packages and Tools Required

- `numpy`  
- `pandas`  
- `matplotlib`  
- `seaborn`  
- `folium`  
- `scikit-learn`  
- `tensorflow`  
- `xgboost`  
- `jupyter notebook`  

---

## 📁 Dataset Source

- Kaggle Taxi Fare Dataset:  
🔗 [New York City Taxi Fare Prediction](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data)

---

## ⚙️ Technologies Used

| Type | Stack |
|------|-------|
| 🔢 ML/Analysis | Python, Jupyter Notebook, Pandas, NumPy, Scikit-learn |
| 📈 Visualization | Matplotlib, Seaborn |
| 🧠 Models | Linear Regression, Random Forest, XGBoost, SVM |
| 🌐 Frontend | HTML (52%), basic CSS |
| 🛠️ Tools | Git, GitHub, JupyterLab |

---

## 🪜 Project Steps

### 1. Environment Setup
- Python environment with Jupyter Notebook
- Installed required libraries

### 2. Data Preprocessing
- Removed incorrect values (e.g., negative fare, zero distances)
- Converted timestamps to extract features like hour, weekday

### 3. Feature Engineering
- Calculated distance using latitude & longitude (Haversine formula)
- Derived time-based features like peak hours

### 4. Model Building
- Applied multiple regression models
- Compared R², MAE, RMSE scores

### 5. HTML Interface
- Built a static HTML form for user input (pickup, dropoff, passengers)
- Results displayed using model predictions
- Ready for integration with Flask backend

---

## 🙋‍♀️ Developed By

**S. Kusuma**  
📧 [Priyakusuma724@gmail.com](mailto:Priyakusuma724@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/s-kusuma-122180203)

---

## 📄 License

This project is open-source and available under the MIT License.

<p align="right">(<a href="#top">back to top</a>)</p>
