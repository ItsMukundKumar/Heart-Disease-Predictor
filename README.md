<style>
   *{
      background-color : grey,
      color : black
   }
   h2{
      color : 2
   }
</style>

<h1> # heart-disease-prediction </h1>

<h3> # ❤️ Heart Disease Prediction using Machine Learning </h3>

<p>This project is a Streamlit-based web application that predicts the likelihood of heart disease based on user input medical data. It uses a trained K-Nearest Neighbors (KNN) model, along with preprocessing using StandardScaler. </p>
## 🚀 Features
<ul>
  <li> Predicts risk of heart disease using a trained ML model </li>
  <li> Clean, interactive GUI made with Streamlit</li>
   <li>Fast and lightweight - works in browser</li>
   <li>Based on real-world medical parameters</li>
</ul>

<h2> ## 📁 Project Structure </h2>
<pre>
heart-disease-prediction/
│
├── app.py # Streamlit application code
├── KNN_heart.pkl # Trained ML model (KNN)
├── scaler.pkl # StandardScaler object
├── columns.pkl # List of feature columns used during training
├── requirements.txt # Python dependencies
└── README.md # Project documentation
</pre>


<h4>You can install all at once using:</h4>

<pre>
''' bash
pip install -r requirements.txt '''  </pre>

<h3>How to Run</h3>
<pre>
Clone the repository or download the project folder.

Navigate to the folder in your terminal or command prompt.

Run the app using Streamlit:
   streamlit run app.py
The app will open automatically in your browser
</pre>
<h2>🧠 Model Details</h2>
<pre><b>
Algorithm: K-Nearest Neighbors (KNN)

Preprocessing: StandardScaler

Input Features: Age, Gender, Chest Pain Type, Blood Pressure, Cholesterol, etc.

Output: Probability or binary prediction for heart disease risk
</b>
</pre>
<h5>📄 License</h5>
<p>
This project is open-source and free to use for educational or personal purposes.</p>


