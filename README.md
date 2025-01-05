# House_price_prediction


The "House Price Prediction" project focuses on predicting housing prices using machine learning techniques. By leveraging popular Python libraries such as NumPy, Pandas, Scikit-learn (sklearn), Matplotlib, Seaborn, and ML Alorithms, this project provides an end-to-end solution for accurate price estimation.

## Project Overview
The "House Price Prediction" project aims to develop a model that can accurately predict housing prices based on various features. This prediction task is of great significance in real estate and finance, enabling informed decision-making for buyers, sellers, and investors. By employing machine learning algorithms and a curated dataset, this project provides a powerful tool for estimating house prices.

## Key Features
1. Data Collection and Processing: The project utilizes the "Housing" dataset, which can be directly downloaded from the Python library. The dataset contains features such as price,area,bedrooms,bathrooms,stories,mainroad,furnishingstatus. Using Pandas, the data is processed and transformed to ensure it is suitable for analysis.

2.Data Visualization: The project employs data visualization techniques to gain insights into the dataset. Matplotlib and Seaborn are utilized to create visualizations such as Box plots, scatter plots, and correlation matrices. These visualizations provide a deeper understanding of the relationships between features and help identify trends and patterns.

3.Train-Test Split: To evaluate the performance of the regression model, the project employs the train-test split technique. The dataset is split into training and testing subsets, ensuring that the model is trained on a portion of the data and evaluated on unseen data. This allows for an accurate assessment of the model's predictive capabilities.

4.Regression Models: The project utilizes the Machine Learing Regression algorithm, such as Linear Regression,Random Forest Regressor,Gradient Boost Regressor,XGBoost,Support Vector regressor,Lasso Reg,Ridge Reg The Scikit-learn library provides an implementation of models that is utilized in this project.

5.Model Evaluation: The project assesses the performance of the regression model using evaluation metrics such as R-squared error and mean absolute error. R-squared error measures the proportion of the variance in the target variable that can be explained by the model, while mean absolute error quantifies the average difference between the predicted and actual house prices. These metrics provide insights into the model's accuracy and precision.

## Conclusion
The "House Price Prediction" project provides a practical solution for estimating housing prices based on various features. By leveraging data collection, preprocessing, visualization, regression modeling, and model evaluation, this project offers a comprehensive approach to addressing the price prediction task. The project utilizes the "Housing" dataset from Scikit-learn, ensuring a reliable and widely accessible data source.

## Model Results
|index|MSE|R2 Score|
|---|---|---|
|Linear Regression|1523019469501\.2913|0\.6463350878895877|
|Random Forest Regressor|1847298709634\.759|0\.5710332343954968|
|Gradient Boost Regressor|1604564599715\.6082|0\.6273992489933706|
|XGBoost|2083551444992\.0|0\.5161722898483276|
|Support Vector regressor|4462190769765\.794|-0\.03617868189555318|
|Lasso Reg|1523019381671\.6501|0\.6463351082847717|
|Ridge Reg|1507286141893\.6584|0\.6499885710111001|
