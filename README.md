# 🚗 Used Car Price Prediction using Random Forest Regression

## 📌 Project Overview

This project predicts the selling price of a used car using **Machine Learning**. It is built using the **Random Forest Regression** algorithm and includes feature engineering, exploratory data analysis (EDA), hyperparameter tuning, feature importance analysis, and price prediction for new cars.

The project is based on the **CarDekho Used Car Dataset** containing information about used vehicles such as manufacturing year, present price, kilometers driven, fuel type, transmission, seller type, and ownership details.

---

## 🎯 Objectives

* Understand regression problems.
* Perform Exploratory Data Analysis (EDA).
* Apply Feature Engineering.
* Encode categorical variables.
* Train a Random Forest Regression model.
* Perform Hyperparameter Tuning using GridSearchCV.
* Evaluate model performance.
* Analyze Feature Importance.
* Predict the selling price of a new car.

---

## 📂 Project Structure

```text
Used_Car_Price_Prediction/
│
├── car data.csv
├── processed_car_data.csv
│
├── Part1_EDA.ipynb
├── Part2_Feature_Engineering.ipynb
├── Part3_Model_Building.ipynb
├── Part4_Hyperparameter_Tuning.ipynb
├── Part5_Prediction.ipynb
│
├── random_forest_model.joblib
├── README.md
└── requirements.txt
```

---

## 📊 Dataset Information

* **Dataset:** CarDekho Used Car Dataset
* **Records:** 301
* **Features:** 9
* **Target Variable:** Selling_Price

### Dataset Features

* Car_Name
* Year
* Present_Price
* Kms_Driven
* Fuel_Type
* Seller_Type
* Transmission
* Owner
* Selling_Price

---

## 🛠 Technologies Used

* Python 3.12+
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Joblib
* Jupyter Notebook / VS Code

---

## 🔄 Project Workflow

1. Load Dataset
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Data Encoding
5. Train-Test Split
6. Random Forest Regression
7. Model Prediction
8. Model Evaluation
9. Hyperparameter Tuning
10. Feature Importance Analysis
11. User Price Prediction

---

## ⚙️ Feature Engineering

The following new features were created:

* Car_Age
* Mileage_per_Year
* Premium_Brand
* High_Mileage

These features improve the predictive performance of the machine learning model.

---

## 🤖 Machine Learning Model

Algorithm Used:

* Random Forest Regressor

Initial Parameters:

* n_estimators = 100
* random_state = 42

Hyperparameter tuning was performed using **GridSearchCV** to obtain the best-performing model.

---

## 📈 Evaluation Metrics

The model was evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

These metrics measure the prediction accuracy and overall performance of the regression model.

---

## 📉 Feature Importance

Random Forest provides feature importance scores, helping identify which input variables have the greatest impact on the predicted selling price.

---

## 🚀 Running the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Used-Car-Price-Prediction.git
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Notebooks

Execute the notebooks in the following order:

1. Part1_EDA.ipynb
2. Part2_Feature_Engineering.ipynb
3. Part3_Model_Building.ipynb
4. Part4_Hyperparameter_Tuning.ipynb
5. Part5_Prediction.ipynb

---

## 📋 Requirements

```
pandas
numpy
matplotlib
scikit-learn
joblib
```

---

## 📌 Future Improvements

* Streamlit Web Application
* Model Deployment
* REST API Integration
* Support for New Car Brands
* Improved Feature Engineering
* Advanced Ensemble Models

---

## 👨‍💻 Author

**Aryan Yadav**

---

## ⭐ If you found this project helpful, consider giving it a star on GitHub!
