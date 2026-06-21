# Movie Recommendation System using Machine Learning

A machine learning-based movie recommendation system built using the MovieLens 1M dataset. The project predicts user ratings and generates personalized movie recommendations using demographic information, movie metadata, rating statistics, and user preference features.

## Features

- Data preprocessing and feature engineering
- User and movie statistical feature generation
- Genre preference modeling
- Multiple ML models:
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor
- Model comparison using MAE, MSE, RMSE, and R²
- Feature importance analysis
- Interactive recommendation interface

## Dataset

MovieLens 1M Dataset

- 1,000,209 ratings
- 6,040 users
- ~3,900 movies

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- ipywidgets

## Results

| Model | R² Score |
|---------|---------|
| Linear Regression | ~0.33 |
| Random Forest | ~0.36 |
| XGBoost | ~0.43 |

XGBoost achieved the best performance and was used for the final recommendation system.

## Future Improvements

- Collaborative Filtering
- Matrix Factorization
- Deep Learning Recommenders
- Hybrid Recommendation Systems

## Author

Aryan Garg  23/EC/37 , Aryan Mishra 23/EC/38
Delhi Technological University (DTU)
