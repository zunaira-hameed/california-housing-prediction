# 🏠 California Housing Price Prediction

A Machine Learning project for predicting California housing prices using different regression models and preprocessing techniques.

---

# 📌 Project Overview

This project uses the California Housing dataset to predict median house values based on different housing and population features.

The project includes:

* Data preprocessing
* Handling missing values
* Encoding categorical data
* Feature engineering
* Model training
* Performance evaluation
* Data visualization

---

# 📊 Dataset Features

The dataset contains the following features:

* longitude
* latitude
* housing_median_age
* total_rooms
* total_bedrooms
* population
* households
* median_income
* ocean_proximity

Target Variable:

* `median_house_value`

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

# 🤖 Machine Learning Models

The following models were used:

1. Linear Regression
2. Random Forest Regressor

---

# ⚙️ Preprocessing Steps

* Removed / handled missing values
* Encoded categorical columns
* Train-test split
* Feature engineering

Additional engineered features:

* rooms_per_household
* bedrooms_per_room
* population_per_household

---

# 📈 Model Performance

### Random Forest Regressor

* R² Score: **0.82**

The Random Forest model performed significantly better than the baseline Linear Regression model.

---

# 📊 Visualizations

The project includes:

* Feature Importance Graph
* Actual vs Predicted Graph

---

# 🚀 How to Run the Project

## 1. Clone Repository

```bash
git clone YOUR_REPOSITORY_LINK
```

---

## 2. Install Dependencies

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## 3. Run Notebook / Python File

```bash
python project.py
```

or open the notebook in Jupyter Notebook.

---

# 📁 Project Structure

```bash
├── housing.csv
├── california_housing.ipynb
├── california_random_forest.pkl
├── README.md
```

---

# 🎯 Future Improvements

* Hyperparameter tuning
* XGBoost implementation
* LightGBM implementation
* Deep learning models

---

# 👩‍💻 Author

Zunaira Hameed

* Machine Learning Enthusiast
* Python Developer
* Data Science Learner

---

# ⭐ GitHub

If you like this project, give it a star ⭐
