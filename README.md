# Diabetes-ML-Cloud
5G-Smart Diabetes: Personalized Diagnosis with Healthcare Big Data Clouds

📌 Overview

This project leverages 5G technology, wearable devices, and machine learning to enable real-time monitoring of diabetic patients at a low cost. By using a combination of Decision Tree, Support Vector Machine (SVM), and Artificial Neural Network (ANN) models, the system predicts patient conditions and alerts doctors accordingly.

🚀 Features

Real-time monitoring: Wearable devices track patient health metrics.

Cloud-based analysis: Patient data is processed using machine learning models.

Ensemble learning: Combines Decision Tree, SVM, and ANN for improved prediction accuracy.

Personalized alerts: Patients and doctors receive condition updates.

🔧 Technology Stack

Programming Language: Python

Machine Learning Models: Decision Tree, SVM, ANN, Ensemble Learning

Cloud Storage & Processing: Cloud application for data storage and processing

📂 Project Structure
├── Cloud/
│   ├── Cloud.py  # Machine Learning models
│   ├── run.bat  # Start cloud server
│   ├── dataset/  # Training dataset
├── User/
│   ├── UserApp.py  # User application interface
│   ├── run.bat  # Start user sensing application
│   ├── data/users.txt  # Test data
├── README.md  # Project documentation

📊 Dataset

The project uses a diabetes dataset with the following attributes:

Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, Outcome

The last column (Outcome) indicates whether a patient has diabetes (1) or not (0).

🛠️ Setup Instructions

1️⃣ Install Dependencies

Ensure you have Python installed, then install the required libraries:
pip install numpy pandas scikit-learn flask

2️⃣ Start the Cloud Server

Navigate to the Cloud folder and run:
python Cloud.py

3️⃣ Start the User Application

Navigate to the User folder and run:
python UserApp.py

4️⃣ Upload Test Data

The cloud server predicts patient conditions based on the uploaded test dataset.

Results are displayed in the user application.

📈 Model Performance

The ensemble model improves prediction accuracy by combining multiple classifiers.

Accuracy comparison of different models is visualized in the accuracy graph.

📸 Screenshots

1️⃣ Uploading dataset in the cloud application2️⃣ Running machine learning models (Decision Tree, SVM, ANN, Ensemble)3️⃣ Accuracy graph for model comparison4️⃣ User application predicting patient condition

🤝 Contribution

Feel free to fork this repository, open issues, and submit pull requests.
