# California House Price Prediction

A machine learning project that predicts median house prices in California districts based on demographic and geographical features. Utilizing the classic California Housing dataset, this project demonstrates a complete data science workflow from exploratory data analysis to model evaluation.

## Key Features

- **Exploratory Data Analysis (EDA)** — Visualizes geographical data, income distributions, and housing attributes to uncover strong correlations (e.g., median income vs. house value).
- **Feature Engineering** — Creates custom attributes such as rooms per household and bedrooms per room to improve predictive accuracy.
- **Data Preprocessing** — Handles missing values, encodes categorical variables (ocean proximity), and scales numerical features for optimal model performance.
- **Predictive Modeling** — Trains and evaluates regression models (Random Forest, Linear Regression) to accurately estimate property values.

## Tech Stack

| Category | Tools |
|----------|-------|
| **Language** | Python |
| **Data Manipulation** | Pandas, NumPy |
| **Machine Learning** | Scikit-learn |
| **Visualization** | Matplotlib, Seaborn |

## Repository Structure

| File | Description |
|------|-------------|
| `housePricePrediction.ipynb` | Main notebook — data loading, EDA, feature engineering, model training, and evaluation |
| `housing.csv` | California Housing dataset |

## Evaluation

The model's performance is measured using Root Mean Squared Error (RMSE), ensuring predictions closely align with actual median house values across California districts.

## Author

**Vati Nisar** — [GitHub](https://github.com/nisarvati)
