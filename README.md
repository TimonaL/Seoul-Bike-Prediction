Predictive Analysis of Bike Rental Demand in Seoul

Objective

To develop and evaluate machine learning predictive models to forecast bike rental demand in Seoul aiming to contribute with resource management and customer service in the bike rental sector.

Problem Statement

The project is about tackling the challenges of analyzing the "SeoulBikeData.csv" dataset to understand and predict bike rental patterns, looking into the impacts of various environmental and temporal factors.

Dataset Overview

• Sourced from Kaggle, the dataset includes key features such as date, hour, temperature among others were key in analyzing trends for bike rental in Seoul.

Data Preprocessing and Feature Engineering:

• Key Python libraries utilized were Pandas, NumPy, Matplotlib, Seaborn, SciKit-Learn and XGBoost.

• Dew point temperature was dropped out due to its high correlation with temperature to prevent multicollinearity.

• Analysis exposed distribution of data having different skewness on features such as Rented Bike Count, Wind Speed, and Solar Radiation.

Model Building, Training, Evaluation:

• Models used include: Linear Regression, Decision Tree Regressor, SVM, KNN, and XGBoost.

• All models are perfectly trained and evaluated based on the dataset.

• Model performance was assessed using mean validation R-squared (Coefficient of Determination) and RMSE (Root Mean Square Error) metrics.

Model Performance Results: Model Mean validations

Baseline Model (Linear Regression) R² 0.6226 : RMSE 1.7167

Decision Tree Regression R² 0.7860 : RMSE 1.2929

Support Vector Regressor (SVM) R² 0.7904 : RMSE 1.2798

K-Nearest Neighbors Regressor (KNN) R² 0.8353 : RMSE 1.1344

XGBoost Regressor R² 0.9043 : RMSE 0.8649

Conclusion

• The XGBoost model provide the performance, with the highest R-squared value and the lowest RMSE, indicating its effectiveness in predicting bike rental demand in Seoul.

• This model, optimized with the best hyperparameters, offers actionable insights for strategic decision-making in bike rental services.

