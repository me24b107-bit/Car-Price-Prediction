# Car Price Prediction Using Machine Learning

## Overview

The price of a used car depends on several factors such as vehicle age, fuel type, transmission, ownership history, and kilometers driven. This project aims to predict the selling price of used cars using machine learning regression techniques.

Multiple regression models were trained and compared to estimate vehicle prices accurately based on market and vehicle attributes. The project demonstrates the complete machine learning workflow, from data preprocessing and exploratory analysis to model evaluation and performance comparison.

---

## Dataset

The dataset contains **301 used car records** with the following attributes:

| Feature | Description |
|----------|-------------|
| Car_Name | Name of the car |
| Year | Manufacturing year |
| Selling_Price | Selling price of the car (Target Variable) |
| Present_Price | Current ex-showroom price |
| Kms_Driven | Distance driven by the vehicle |
| Fuel_Type | Petrol / Diesel / CNG |
| Seller_Type | Dealer / Individual |
| Transmission | Manual / Automatic |
| Owner | Number of previous owners |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Project Workflow

### Data Preprocessing

- Removed irrelevant features
- Handled categorical variables
- Applied feature encoding
- Prepared training and testing datasets

### Exploratory Data Analysis

- Analyzed vehicle price distributions
- Studied relationships between vehicle attributes and selling price
- Visualized correlations among features

### Model Development

The following regression models were implemented and compared:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression

### Model Evaluation

Models were evaluated using:

- R² Score
- Training Performance
- Validation Performance

---

## Exploratory Analysis

Key observations from the dataset:

- Newer vehicles generally have higher selling prices.
- Present price strongly influences resale value.
- Vehicles with lower mileage tend to retain more value.
- Fuel type and transmission significantly impact pricing.
- Individual sellers typically list vehicles at lower prices than dealers.

---

## Results

| Model | R² Score |
|---------|---------|
| Linear Regression | 0.77 |
| Ridge Regression | 0.77 |
| Lasso Regression | 0.77 |
| Elastic Net Regression | 0.77 |

### Best Performance

- Achieved an **R² score of 0.77** on unseen data.
- Successfully captured key relationships between vehicle characteristics and resale value.
- Demonstrated the effectiveness of regression techniques for used car price estimation.

---

## Project Structure

```text
Car-Price-Prediction/
│
├── car data.csv
├── car_price_predict.py
├── README.md
│
├── images/
│   ├── correlation_heatmap.png
│   ├── price_distribution.png
│   └── feature_analysis.png
│
└── requirements.txt
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Car-Price-Prediction.git

cd Car-Price-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

Run the project using:

```bash
python Car_Price_Prediction.py
```

The script will:

1. Load and preprocess the dataset.
2. Perform exploratory data analysis.
3. Train multiple regression models.
4. Compare model performance.
5. Display evaluation metrics.

---

## Applications

- Used Car Price Estimation
- Automotive Market Analysis
- Vehicle Valuation Systems
- Online Car Marketplace Platforms
- Pricing Recommendation Tools

---

## Future Improvements

- Increase dataset size for improved generalization.
- Perform hyperparameter tuning.
- Implement ensemble-based regression techniques.
- Deploy the model using Streamlit or Flask.
- Integrate real-time market pricing data.

---

## Key Learnings

- Data preprocessing and feature encoding
- Exploratory data analysis
- Regression model implementation
- Model comparison and evaluation
- Predictive analytics using machine learning

---

## Author

Sathwik Gorrela

B.Tech Mechanical Engineering  
Indian Institute of Technology Madras
8. Transmission : Defines whether the car is manual or automatic.

9. Owner : Defines the number of owners the car has previously had.
