Objective:
The aim of this project was to build a classifier to predict next-day rainfall in Australia using historical weather data. This project was completed as part of the IBM Skills Network practice labs.

Project Overview:
The dataset contained daily weather observations with variables such as temperature, humidity, pressure, and rainfall history. Data preprocessing involved handling missing values, encoding categorical fields (such as weather station identifiers), and scaling continuous features. Feature engineering was applied to improve predictive performance, including the creation of lagged rainfall indicators, rolling averages for humidity and temperature, and seasonal features such as month and day-of-week.

Machine learning classifiers, including Logistic Regression, Random Forest, and Gradient Boosting, were trained on the dataset. Hyperparameter tuning was performed using GridSearchCV to identify the optimal settings for each model. Evaluation was carried out using accuracy, F1-score, and confusion matrix analysis to ensure balanced performance between the “rain” and “no rain” outcomes, particularly since rainfall events were less frequent and the data exhibited class imbalance.

Key Results:

Models successfully predicted next-day rainfall with strong performance on validation data.

Confusion matrix analysis ensured balanced classification, avoiding bias toward the majority “no rain” class.

The project highlighted the importance of feature engineering in climate-related data and reinforced strategies for handling imbalanced classification problems.

Tech Stack: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
