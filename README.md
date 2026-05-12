# Restaurant Success Prediction Framework

This project presents a machine learning framework for predicting high-potential restaurant investments in European markets using TripAdvisor data.

## Project Objective

The goal was to build a decision-support system for a risk-averse investment scenario, where the cost of investing in a failed business (False Positive) is significantly higher than missing a successful opportunity (False Negative).

Therefore, the model was optimized for **high precision**, targeting approximately **80% confidence** in selected investment candidates.

## Dataset

The project uses the TripAdvisor European Restaurants dataset available on Kaggle:

TripAdvisor European Restaurants Dataset (Kaggle) -> Link: https://www.kaggle.com/datasets/stefanoleone992/tripadvisor-european-restaurants

Due to the dataset size, it is not included directly in this repository.  
To run the notebook locally:

1. Download the dataset manually from the Kaggle link above.
2. Upload the CSV file into your local environment or Google Colab notebook.
3. Update the dataset path in the notebook if needed.

The dataset includes:

- Restaurant metadata
- Cuisine categories
- Geographic information
- Operational attributes
- User-generated ratings

## Workflow

The project includes:

- Exploratory Data Analysis (EDA)
- Data cleaning and leakage prevention
- Feature engineering
- Missing value handling
- Target encoding for high-cardinality features
- Model benchmarking
- Threshold optimization for business-specific precision targets

## Models Evaluated

Several classification models were benchmarked:

- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost
- AdaBoost



## Key Takeaway

This project demonstrates how machine learning can be adapted to business-specific decision strategies, where model success is defined not by generic accuracy, but by alignment with real-world risk constraints.
