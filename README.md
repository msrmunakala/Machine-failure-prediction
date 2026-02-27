📌 Project Overview

This project implements a Predictive Maintenance System using Machine Learning to predict machine failures based on operational sensor data.
The model is deployed and tested using PrediBot, allowing real-time predictions through a web interface.

The goal is to reduce unplanned downtime, optimize maintenance schedules, and improve industrial efficiency.

🔗 Live Prediction Demo

👉 PrediBot Deployment Link
https://predibot.com/predict/fmYr1BDKjyM

Use this link to input machine parameters and get instant failure predictions.

🧠 Problem Statement

Unexpected machine failures in manufacturing environments lead to:

Production loss

Increased maintenance cost

Safety risks

This project predicts whether a machine will fail or not using historical sensor data and machine conditions.

📂 Dataset Information

Dataset Name: AI4I 2020 Predictive Maintenance Dataset

Source: Industrial sensor data simulation

File Used: ai4i2020.csv

📊 Key Features
Feature	Description
Air temperature	Temperature of air in Kelvin
Process temperature	Temperature during operation
Rotational speed	Speed in rpm
Torque	Applied torque
Tool wear	Wear time in minutes
Target	Machine failure (0 / 1)
⚙️ Tech Stack Used

Programming Language: Python

Libraries:

NumPy

Pandas

Matplotlib / Seaborn

Scikit-learn

Model Deployment: PrediBot

Environment: Jupyter Notebook

🔬 Machine Learning Workflow

Data Loading & Exploration

Data Cleaning & Preprocessing

Feature Selection

Train-Test Split

Model Training

Model Evaluation

Deployment using PrediBot

🤖 Models Implemented

Logistic Regression

Random Forest Classifier

Support Vector Machine (SVM)

✅ Best Performing Model selected based on:

Accuracy

Precision

Recall

F1-score

📈 Results & Performance

Achieved high accuracy on test data

Successfully predicts machine failure in advance

Robust performance on unseen inputs via PrediBot

🖥️ Project Structure
├── ai4i2020.csv
├── invotex-1.ipynb
├── notebookfaaef006c5.ipynb
├── README.md
▶️ How to Run Locally

Clone the repository

git clone https://github.com/your-username/predictive-maintenance-ml.git

Install dependencies

pip install numpy pandas matplotlib seaborn scikit-learn

Run the notebook

jupyter notebook
🌐 Deployment

The trained model is deployed using PrediBot, enabling:

Browser-based predictions

Real-time inference

Easy sharing without backend setup

🎯 Use Cases

Smart Manufacturing

Industry 4.0 Applications

Predictive Analytics

Maintenance Optimization

📌 Future Enhancements

Deep Learning models

Real-time IoT data integration

Dashboard using Streamlit

Multi-class failure prediction

👨‍💻 Author

Munakala Madhusudhan Rao

Machine Learning Enthusiast

Python Developer

Aspiring AI Engineer

⭐ Acknowledgements

AI4I 2020 Dataset

Scikit-learn Documentation

PrediBot Platform
