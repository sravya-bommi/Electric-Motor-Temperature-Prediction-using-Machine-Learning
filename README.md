# Electric-Motor-Temperature-Prediction-using-Machine-Learning
🔥 Electric Motor Temperature Prediction System
📌 About the Project

This project focuses on predicting the operating temperature of an electric motor using Machine Learning techniques. Electric motors are widely used in industries, and abnormal temperature rise may lead to performance issues or equipment failure.

By analyzing sensor data such as speed, torque, voltage, and current, this system predicts motor temperature to support early fault detection and maintenance planning.

🎯 Project Goals

Build ML models to estimate motor temperature

Reduce the risk of overheating

Improve operational reliability

Support predictive maintenance in industrial environments

🧠 Machine Learning Approach

Multiple regression models were implemented and evaluated to improve prediction accuracy:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Support Vector Machine (SVM)

The final selected model is saved and used in the Flask web application for real-time prediction.

🛠️ Tech Stack

Programming Language

Python

Libraries

Scikit-learn

Pandas

NumPy

Matplotlib

Web Development

Flask (Backend)

HTML & CSS (Frontend)

📁 Project Directory Structure
Electric-Motor-Temperature/
│
├── Main/
│   ├── app.py
│   ├── train_model.py
│   ├── sensor_model_train.py
│   ├── best_model.pkl
│   ├── scaler.pkl
│
├── templates/
│   ├── index.html
│   ├── sensor.html
│   ├── Manual.html
│
├── Output/
│   ├── Home.png
│   ├── Manual.png
│   ├── Sensor.png
│   └── Prediction_Result.png
│
├── measures_v2.csv   (Dataset - optional)
├── requirements.txt
└── README.md
📊 Dataset Information

The model was trained using a motor sensor dataset (measures_v2.csv) containing parameters such as:

Motor Speed

Torque

Voltage

Current

Ambient Conditions

⚠️ Large dataset files and trained .pkl model files may not be included in this repository due to GitHub size limitations.

🚀 How to Execute the Project:
-------------------------------
Step 1: Clone the repository
git clone <your-repository-link>
cd Electric-Motor-Temperature

Step 2: Install dependencies
pip install -r requirements.txt

Step 3: Train the models (if model files are not available)
python train_model.py
python sensor_model_train.py

Step 4: Run Flask Application
python app.py

Then open your browser:
-----------------------
http://127.0.0.1:5000/
💡 Key Features

Manual data input for temperature prediction

Sensor-based prediction module

Model comparison during training

Simple and user-friendly web interface

Separate training and prediction scripts

🏭 Real-World Use Cases
------------------------

Industrial equipment monitoring

Smart manufacturing systems

Preventive maintenance solutions

Motor health tracking systems

🔄 Future Improvements:
-----------------------
Integration with real-time IoT sensor data

Cloud deployment (AWS / Azure / GCP)

Model performance dashboard

REST API version for integration

📌 Summary

This project demonstrates the application of Machine Learning in predicting electric motor temperature using sensor-based data. It highlights how data-driven models can assist industries in monitoring motor health and minimizing unexpected failures.
