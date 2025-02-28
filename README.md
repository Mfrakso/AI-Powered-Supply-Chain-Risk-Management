AI-Powered Supply Chain Risk Management

Overview

This project leverages AI techniques to enhance supply chain risk management by utilizing data preprocessing, exploratory data analysis (EDA), predictive modeling, and visualization. The aim is to improve risk prediction, optimize logistics, and automate decision-making for better operational efficiency.

Dataset

The dataset used is DataCo Supply Chain Dataset.

Key features include: Sales, Order Details, Shipping Mode, Customer Information, and Product Categories.

Missing values in Customer Zipcode, Order Zipcode, and Customer Name are handled appropriately.

Unnecessary columns such as Customer Email, Product Description, and Product Image are removed for optimization.

Data Preprocessing

Columns are cleaned, standardized, and renamed for consistency.

Handling missing values through imputation and transformation.

Aggregating data based on different groupings such as Delivery Status, Market, Region, and Shipping Mode.

Exploratory Data Analysis (EDA)

Sales Distribution Analysis: Visualized using histograms.

Geographical Analysis: Choropleth maps are used to display country-wise order profits.

Category-Wise Sales and Loss Analysis: Bar charts are created to identify high-loss categories.

Correlation Analysis: Heatmaps are generated to understand relationships between numerical features.

Prediction Model

Various machine learning models are used to predict Days for Shipping (Real) based on order details.

Encoding categorical variables using Label Encoding.

Feature scaling using Decimal Scaling.

Machine Learning Models Used

The following models are trained and evaluated:

Decision Tree

Random Forest

K-Nearest Neighbors

Naive Bayes

Linear Discriminant Analysis

XGBoost

CatBoost

LightGBM

AdaBoost

Perceptron

Model Training & Evaluation

The dataset is split into training and testing sets.

Each model is trained and evaluated using Accuracy Score.

A bar chart visualizes the model performance for comparison.

Visualization

Various visualizations are implemented using Seaborn and Plotly.

Sales trends, Category-wise losses, and Geographical profit distributions are analyzed.

Correlation heatmaps help identify feature relationships for better model training.

Conclusion

This project demonstrates how AI-driven models can optimize supply chain risk management by predicting disruptions, assessing supplier performance, and automating risk mitigation. Future improvements include integrating blockchain for transparency, real-time IoT data for enhanced monitoring, and adaptive AI models for better forecasting.

