#  ValueMyCar - Car Price Prediction

## 📌 Project Overview

ValueMyCar is a Machine Learning web application that predicts the selling price of used cars based on user inputs.
This project demonstrates data preprocessing, model training, evaluation, and deployment using Flask.

---

## 📊 Dataset

* Source: CarDekho dataset
* Features used:

  * Vehicle Age
  * Kilometers Driven
  * Mileage
  * Engine
  * Max Power
  * Seats
  * Seller Type
  * Fuel Type
  * Transmission

### 🔧 Data Preprocessing

* Removed missing values
* Converted categorical variables using encoding
* Feature selection based on relevance
* Scaled/cleaned numerical values

---

## 🧠 Model Implementation

### Algorithms Used:

* Random Forest Regressor (Primary model)

### Steps:

1. Data Cleaning
2. Feature Engineering
3. Train-Test Split
4. Model Training
5. Model Saving using Pickle

---

## 📈 Model Evaluation

* **R² Score**: 0.937379181346118
* **RMSE**: (Add if available)

👉 The model performs well in predicting car prices with reasonable accuracy.

---

## 📦 Model File

The trained model file is large and not included in this repository.

🔗 Download the model from Google Drive:
https://drive.google.com/file/d/1-Lv5PicmM5xFuYwjQpLNzb_A5KHTfVPT/view?usp=sharing

After downloading, place it in the root folder:

best_model.pkl

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python app.py
```

Then open:
http://127.0.0.1:8001/

---

## 📷 Screenshots

### 🏠 Example 1 - Standard Car Prediction

![Output1](Output/Output1.png)

### 🚙 Example 2 - Older Car Prediction

![Output2](Output/Output2.png)

### 🚘 Example 3 - Premium Car Prediction

![Output3](Output/Output3.png)

---

## 📊 Results & Insights

* Newer cars have higher resale value
* Cars with lower kilometers driven have better pricing
* Engine power and fuel type influence price significantly
* Dealer cars generally have higher predicted prices

---

## 💡 Future Improvements

* Include car brand and model features
* Use advanced models like XGBoost
* Deploy the application online
* Improve accuracy with more data

---

## 👨‍💻 Author

James Alwin
