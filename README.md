# House-price--prediction-ML
# House Price Prediction (Machine Learning)

This project focuses on predicting house prices using regression models.
It includes exploratory data analysis (EDA), data preprocessing, and model evaluation.

##  Key Highlights
- Exploratory Data Analysis with visualizations
- Data preprocessing and feature encoding
- Regression models for house price prediction
- Model evaluation using MAE, MSE, RMSE, and R²

##  Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

##  Project Status
Work in progress

## Model Selection & Results
Multiple regression models were trained and evaluated to identify the best-performing approach for house price prediction. The comparison was based on error metrics (MAE, MSE, RMSE) and the coefficient of determination (R²).

Among the evaluated models, **Linear Regression** achieved performance comparable to more complex ensemble models while maintaining simplicity and interpretability. Therefore, it was selected as the final model.

The evaluation showed that linear models performed competitively, indicating that the dataset exhibits largely linear relationships between features and house prices.

## Model Persistence
The final trained model and preprocessing scaler were saved using `joblib` to enable reuse and deployment without retraining.
`best_house_price_model.pkl` – trained regression model  
`scaler.pkl` – feature scaling object

 ## Prediction Analysis
A comparison between actual and predicted house prices was visualized to assess model performance. The predictions closely followed the actual values, indicating good generalization on unseen data.

## Project Structure
House-Price-Prediction/
├── data/
│   └── house_price.csv
├── notebooks/
│   └── house_price_prediction.ipynb
├── models/
│   ├── best_house_price_model.pkl
│   └── scaler.pkl
├── README.md
└── requirements.txt

## Conclusion
This project demonstrates a complete machine learning pipeline for house price prediction, including data exploration, preprocessing, model training, evaluation, and selection. The final model was chosen based on objective performance metrics and saved for future use, making the solution both effective and reusable.


## Future Improvements
- Hyperparameter tuning for ensemble models
- Inclusion of additional location-based features
- Deployment as a web application

