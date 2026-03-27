# Insurance Price Prediction

## Project Overview

Insurance companies calculate medical insurance costs based on several personal and lifestyle factors. This project uses **Machine Learning techniques to predict insurance charges** based on attributes such as age, BMI, smoking habits, number of children, and region.

The objective of this project is to analyze the dataset, understand the factors affecting insurance costs, and build a predictive model that estimates the insurance charges accurately.

---

## Problem Statement

Predict the **medical insurance charges** of an individual using demographic and health-related features.

---

## Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical computations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Scikit-learn** – Machine learning algorithms
* **Jupyter Notebook** – Development environment

---

## Dataset Description

The dataset contains demographic and health-related information used to calculate insurance costs.

### Features

* **Age** – Age of the individual
* **Sex** – Gender of the individual
* **BMI** – Body Mass Index
* **Children** – Number of dependents covered by insurance
* **Smoker** – Whether the individual smokes or not
* **Region** – Residential region in the US
* **Charges** – Medical insurance cost (Target Variable)

---

## Project Workflow

### 1. Data Collection

Import the insurance dataset and required Python libraries.

### 2. Data Preprocessing

* Handle missing values
* Convert categorical variables to numerical format
* Prepare dataset for modeling

### 3. Exploratory Data Analysis (EDA)

* Analyze distribution of features
* Identify relationships between variables
* Visualize patterns affecting insurance charges

### 4. Feature Engineering

* Select relevant features
* Transform variables where necessary

### 5. Model Building

Train machine learning models using **Scikit-learn regression algorithms**.

### 6. Model Evaluation

Evaluate model performance using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* R² Score

---

## Project Structure

```
Insurance-Price-Prediction
│
├── Insurance_price_prediction.ipynb
├── README.md
```

---

## Results

The machine learning model successfully predicts insurance charges based on the input features. The project demonstrates how machine learning can assist insurance companies in estimating healthcare costs more efficiently.

---

## Future Improvements

* Apply advanced regression models like **Random Forest, Gradient Boosting, and XGBoost**
* Perform **hyperparameter tuning**
* Deploy the model using **Flask, Streamlit, or a web dashboard**
* Integrate the model into a **real-time prediction system**

---

## Author

**Saniya Khan**
Software Engineering Student
Machine Learning & Data Analytics Enthusiast
