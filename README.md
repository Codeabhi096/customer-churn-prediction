<h2>customer Churn Prediction</h2>
Overview
This is a machine learning project to predict customer churn in a telecom company. The goal is to build a model that can accurately identify customers who are likely to leave the company so that proactive steps can be taken to retain them. The project also aims at finding churn risk score and factors influencing churing of customers.

The project involves data cleaning and preprocessing, exploratory data analysis, feature selection, model training and evaluation, and deployment of the model as a web application using Flask.

Dataset
The dataset used for this project is the Telecom Customer Churn dataset, which can was provided by DataMites Institute. It contains information about customers, such as their account length, international plan, voicemail messages, day and night calls, and charges, as well as whether they churned or not.

Requirements
The project requires the following libraries:

pandas
numpy
matplotlib
seaborn
MGD_Outliers
scikit-learn
xgboost
flask
Usage
To run the project, follow these steps:

Clone the repository: git clone https://github.com/mdushetwar/Customer_Churn.git
Install the required libraries: pip install -r requirements.txt
Run the web application: python app.py
Open a web browser and go to http://localhost:5000
The web application allows users to enter information about a customer and get a prediction of whether they are likely to churn or not.
Files
app.py: Flask web application to predict customer churn
churn_prediction.ipynb: Jupyter notebook with the code for data cleaning, preprocessing, EDA, feature selection, and model training and evaluation
requirements.txt: List of required libraries for the project
Results
The model achieved an F1 score of 0.97 on the test set, indicating that it can accurately predict customer churn. The top five features that influence customer churn are account length, customer service calls, international plan, voicemail messages, and day charge.

Future Work
Possible future work includes:

Collecting more data to improve the accuracy of the model
Using more advanced machine learning techniques, such as deep learning, to build a more accurate model
Deploying the model in a production environment to make it available to customers in real-time
Credits
This project was completed as part of a internship offered by DataMite and Rubixe. The dataset used for this project was obtained from DataMites.

Contributors
Mayur Dushetwar (www.mayurdushetwar.com)

Amit Kumar
