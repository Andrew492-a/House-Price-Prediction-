# 🏠 House Price Prediction

An end-to-end Machine Learning project that predicts residential property prices using structured property features and textual listing information.

The project includes complete data preprocessing, feature engineering, exploratory data analysis, model comparison, hyperparameter tuning, and deployment-ready artifacts.

---

## Project Overview

This project predicts house prices from real estate listings collected from multiple Indian cities.

The workflow includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Text Processing using TF-IDF
- Feature Encoding
- Model Comparison
- Cross Validation
- Model Export

---

## Dataset

The dataset contains approximately **187,000+** residential property listings.

Features include:

- Property Title
- Description
- Location
- BHK
- Current Floor
- Total Floors
- Transaction Type
- Furnishing
- Facing Direction
- Overlooking
- Society
- Bathrooms
- Balconies
- Car Parking
- Ownership
- Carpet Area
- Super Area

Target:

- **Price (INR)**

---

## Machine Learning Models

The following regression models were evaluated:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Decision Tree Regressor
- Random Forest Regressor
- Extra Trees Regressor
- XGBoost
- LightGBM
- CatBoost
- Stacking Regressor

The best-performing model was selected using evaluation metrics on the test dataset.

---

## Evaluation Metrics

The models were compared using:

- MAE
- RMSE
- R² Score
- Cross Validation

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost
- Matplotlib
- Seaborn
- Joblib

---

## Project Structure

```
house-price-prediction/
│
├── notebooks/
│   └── house_price_prediction.ipynb
│
├── models/
│   ├── feature_meta.json
│   └── locations.json
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Notes

The trained model is not included in this repository because it exceeds GitHub's file size limit. Running the notebook will regenerate the model locally.

---

## Future Improvements

- FastAPI backend
- React frontend
- Docker deployment
- Cloud deployment
- Model monitoring