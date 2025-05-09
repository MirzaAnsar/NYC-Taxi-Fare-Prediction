# NYC Taxi Fare Prediction – Big Data ML Pipeline

## 🗂️ Project Overview
This project involves predicting NYC taxi fares using a massive dataset (55M+ rows) with Apache Spark and AWS cloud services. The goal is to create a scalable machine learning pipeline to estimate fares based on trip distance, pickup/dropoff locations, and timestamps.

## ⚙️ Technologies Used
- Python
- Apache Spark (PySpark)
- AWS S3 & Athena
- Pandas, NumPy, Matplotlib
- Spark MLlib (Gradient Boosted Trees, Linear Regression)

## 📊 Dataset
Original data comes from the NYC Taxi & Limousine Commission and was accessed through [Kaggle](https://www.kaggle.com/c/nyc-taxi-fare-prediction/data) and stored in AWS S3.

## 📈 What I Did
- Cleaned and processed 55M+ rows using PySpark.
- Engineered features like trip distance using Haversine formula.
- Queried subsets of data using AWS Athena and S3.
- Trained GBT and Linear Regression models using Spark MLlib.
- Evaluated model performance using RMSE (best: **4.64**).
- Visualized results using matplotlib.

## 📁 Files
- `nyc_taxi_fare_prediction.ipynb` – Full end-to-end pipeline in Jupyter.
- `requirements.txt` – List of libraries used (optional).

## 🚀 Results
Achieved a final RMSE of **4.64**, demonstrating the effectiveness of distributed computing and ensemble models on large-scale datasets.

## 🙋‍♂️ Author
Mirza Ansar Baig 
