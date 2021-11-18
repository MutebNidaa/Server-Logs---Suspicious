# Server-Logs---Suspicious


# Abstract
Coburg Intrusion Detection Data Sets (CIDDS) is a concept to create evaluation data sets for anomaly-based network intrusion detection systems. The goal of this project was to use classification models to predict the suspicious or normal or unknown in the network in order to help improve prevent cyberattacks and maintain stability. leveraging categorical feature engineering along with a random forest model to achieve promising results for this multiclass problem. After refining a model, I built an interactive visualization and communicate my results using the seaborn library.

# Design
This project aims to create a classifier to identify the suspicious or normal or unknown. The external server attack logs are the most interesting part. These days sophisticated systems are being built to encounter Server attacks and suspicious content. Working in building a model to predict an attack session. This project uses data provided by Kaggle. This data contains features that Server-Logs Suspicious ,These Logs are categorized as suspicious or normal or unknown, Server-Logs are a very large suspicion of this dataset.  

# Data
Dataset I obtained was from Kaggle https://www.kaggle.com/kartikjaspal/server-logssuspicious. 
This dataset is uploaded to check what factors contribute to server anomalies. Dataset: 172838 rows, 16 columns, Included columns: Time and duration of attack, Source and destination IP, Packets, bytes, flows, and flags, Type, ID, and label/class I am planning to use deep learning model such KNN, RNN and Logistic Regression. I will plan to conduct this model in which differentiate between normal and suspicious attacks.
