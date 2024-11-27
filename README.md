# Network-Intrusion
This project focused on detecting anomalies in network data and implementing a real-time prediction system to monitor operational statuses by building an end to end machine learning pipeline using PySpark and Flask.

![image](https://ars.els-cdn.com/content/image/3-s2.0-B978032390193200003X-f05-03-9780323901932.jpg)

Key Highlights of the Project:

1, Data Preprocessing:
 • Utilized Pandas, PySpark, and NumPy for data cleaning and transformation.
 • Scaled features using StandardScaler and encoded categorical variables using StringIndexer.

2, Machine Learning Models:
 • Implemented Logistic Regression and Decision Tree Classifiers from PySpark MLlib to perform multi-class classification on network intrusion data.
 • Used One-vs-Rest Classifier for handling multiple classes effectively.

3, Real-Time Predictions:
 • Developed a Flask API that integrates the trained model for real-time predictions.
 • The system predicts operational statuses and triggers alerts for potential threats.

4, Feature Engineering & Visualisation:
 • Employed VectorAssembler for assembling features into vectors for model input.
 • Visualized model weights and important features using Matplotlib to gain insights into feature impact on predictions.

5, Model Evaluation & Tuning:
 • Used MulticlassClassificationEvaluator to evaluate model performance with metrics like accuracy weightedrecall, weightedprecision and F1-score.

Deployment Pipeline:
 • Created a seamless pipeline from data preparation to post-processing using Flask for real-time deployment and serving predictions.
