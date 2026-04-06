# Customer Satisfaction Prediction from Review Text

This project focuses on predicting customer satisfaction based on large-scale review data using machine learning techniques.

## Project Overview

- Dataset: 2.1M+ Trustpilot reviews with ratings (1–5 stars)
- Goal: Predict customer satisfaction from review text
- Approach:
  - Exploratory Data Analysis (EDA)
  - Data cleaning and preprocessing
  - Feature engineering (text + numerical features)
  - Machine learning modeling and evaluation

## Key Challenges

- Large-scale dataset (2M+ records)
- Severe class imbalance (majority: 5★ reviews)
- Unstructured text data

## Modeling Approach

- Text vectorization using **TF-IDF**
- Additional feature engineering from review metadata
- Tested multiple approaches:
  - Classical models (Logistic Regression)
  - Embedding-based approaches
  - Transformer-based approaches (conceptual)

## Results

- Best model: **TF-IDF + Logistic Regression**
- Multi-class classification (1–5 stars):
  - F1-score: **0.73**
- Binary classification (positive vs negative):
  - F1-score: **0.94**
- High recall for negative reviews → useful for business alert systems

## Business Value

- Automatic detection of dissatisfied customers
- Scalable analysis of large volumes of customer feedback
- Supports data-driven decision-making and customer experience improvement

## My Contribution

This was a team project (3 members). I contributed to:
- Data preprocessing and cleaning
- Exploratory data analysis (EDA)
- Feature engineering
- Model evaluation and interpretation

## Tools & Technologies

- Python (pandas, NumPy, scikit-learn)
- NLP techniques (TF-IDF, text preprocessing)
- MLflow (experiment tracking)
- SHAP (model explainability)
- Jupyter Notebook
  
## Additional Resources

- Business Report (project context and impact)
- Modeling Report (technical details and experiments)
