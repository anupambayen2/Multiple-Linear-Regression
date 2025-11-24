Project Summary: Profit Prediction Using Multiple Linear Regression

This project applies Multiple Linear Regression to predict the profit of startups based on multiple business factors. It is part of my daily GitHub uploads to track progress in machine learning.

📌 Objective

To build and evaluate a regression model that predicts company profit using multiple input variables.

📊 Dataset

The dataset (50_Startups.csv) contains:

50 rows

Features:

R&D Spend

Administration

Marketing Spend

State (categorical)

Target:

Profit

R&D Spend shows the strongest positive correlation with profit.

🛠️ Steps Performed

Loaded and explored the dataset

Visualized correlations between features and profit

Converted the categorical column (“State”) using one-hot encoding

Trained a Multiple Linear Regression model

Predicted profit values

Evaluated the model using R² and other metrics

📈 Key Insight

The model shows that:

R&D Spend is the most significant predictor of profit

Administration and Marketing Spend have weaker influence

The State variable has minimal impact after encoding

🧪 Outputs

Predicted profit values

Model performance metrics

Insights on key contributing factors

🚀 Conclusion

This project demonstrates how multiple features can be used together to build a more realistic and powerful regression model compared to simple linear regression. It also introduces important preprocessing steps like encoding categorical data.
