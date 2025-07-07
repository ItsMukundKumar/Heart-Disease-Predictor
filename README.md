# heart-disease-prediction

# ❤️ Heart Disease Prediction using Machine Learning 

This project is a Streamlit-based web application that predicts the likelihood of heart disease based on user input medical data. It uses a trained K-Nearest Neighbors (KNN) model, along with preprocessing using StandardScaler.

## 🚀 Features

- Predicts risk of heart disease using a trained ML model
- Clean, interactive GUI made with Streamlit
- Fast and lightweight - works in browser
- Based on real-world medical parameters

## 📁 Project Structure
heart-disease-prediction/
│
├── app.py # Streamlit application code
├── KNN_heart.pkl # Trained ML model (KNN)
├── scaler.pkl # StandardScaler object
├── columns.pkl # List of feature columns used during training
├── requirements.txt # Python dependencies
└── README.md # Project documentation


->You can install all at once using:

''' bash
pip install -r requirements.txt '''

How to Run
Clone the repository or download the project folder.

Navigate to the folder in your terminal or command prompt.

Run the app using Streamlit:
   streamlit run app.py
The app will open automatically in your browser


🧠 Model Details
Algorithm: K-Nearest Neighbors (KNN)

Preprocessing: StandardScaler

Input Features: Age, Gender, Chest Pain Type, Blood Pressure, Cholesterol, etc.

Output: Probability or binary prediction for heart disease risk

📄 License
This project is open-source and free to use for educational or personal purposes.


