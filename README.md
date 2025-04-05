# codealpha_tasks
1) Iris-Flower-Classification-ML-Model
Objective: Classify iris flower species based on sepal and petal dimensions.

Libraries: Python, Scikit-learn, Pandas, Matplotlib.

The Iris flower classification model serves as an excellent introduction to machine learning concepts, including data preprocessing, model training, and evaluation. It demonstrates how to apply various classification algorithms to a real-world problem and provides insights into the importance of feature selection and model evaluation metrics.

2) Car-Price-Prediction-ML-model
This project implements a machine learning solution to accurately predict car prices based on various vehicle attributes. By analyzing historical car data, the system identifies patterns and relationships between car features and their market values, enabling precise price estimations for new vehicles.

3) Sales-Prediction-using-Python

The aim of this project is to predict sales based on advertising expenditure using the given dataset. The dataset contains information about advertising spending on different platforms (TV, Radio, and Newspaper) and the corresponding sales amount.

Data Exploration and Preprocessing :
-The shape and descriptive statistics for the dataset were displayed using df.shape and df.describe(). 
-A pair plot was created to visualize the relationship between advertising expenditure on TV, Radio, Newspaper, and sales using seaborn.pairplot. 
-Histograms were plotted to observe the distribution of advertising expenditure on TV, Radio, and Newspaper using matplotlib.pyplot.hist.

Correlation Analysis: A correlation matrix heatmap was plotted to observe the correlation between advertising expenditure on TV, Radio, Newspaper, and sales using seaborn.heatmap.

Model Training :The data was split into training and testing sets using train_test_split. Linear regression model was trained on the training data using sklearn.linear_model.LinearRegression.

Model Prediction: The model was used to predict sales based on advertising expenditure on TV for the test set using model.predict(X_test) and the corresponding advertising expenditure on TV in the test set. The model coefficients and intercept were obtained using model.coef_ and model.intercept_.
The predictions and actual sales values were plotted using matplotlib.pyplot.plot and matplotlib.pyplot.scatter.
