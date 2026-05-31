Movie Rating Prediction using Machine Learning

This project was developed to predict movie ratings using machine learning techniques based on different movie attributes such as genre, director, actors, votes, duration, and release year.

The project started with data preprocessing where missing values were handled and unnecessary inconsistencies in the dataset were cleaned. Categorical features like genre, director, and actor names were converted into numerical format using Label Encoding so that machine learning algorithms could process the data effectively.

Different regression models were trained and tested including:

-Linear Regression
-Decision Tree Regressor
-Random Forest Regressor

After comparing the performance of all models using R² Score, Random Forest Regressor produced the best results among the tested algorithms.

The project also includes:

-Data visualization
-Model comparison
-Feature importance analysis
-Custom movie rating prediction
-Model saving using Joblib

One interesting observation from the project was that the number of votes had a strong influence on movie ratings according to the feature importance analysis.

Technologies Used:

-Python
-Pandas
-NumPy
-Matplotlib
-Scikit-learn
-Google Colab

This project helped in understanding the complete machine learning workflow including preprocessing, feature engineering, model training, evaluation, and prediction.
