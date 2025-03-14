📌 Customer Churn Prediction using Streamlit<br>
🚀 Overview<br>
This is a Customer Churn Prediction Web App built using Streamlit. The app allows users to input customer details and predicts whether a customer is likely to churn based on a pre-trained machine learning model.<br>

📂 Project Structure<br>
📦 Customer-Churn-Prediction
│-- app.py                # Streamlit Web App
│-- model.pkl             # Trained ML Model
│-- scaler.pkl            # Scaler for Input Data
│-- requirements.txt      # Dependencies
│-- README.md             # Project Documentation
<br>
📌 Features<br>
✅ Simple and Interactive UI using Streamlit<br>
✅ Takes Age, Gender, Tenure, and Monthly Recharge as inputs<br>
✅ Predicts whether a customer will Churn (Yes/No)<br>
✅ Uses Joblib for loading the pre-trained model<br>

⚙️ How to Run the App<br>
1️⃣ Install Dependencies<br>
First, install the required Python packages using:<br>
pip install -r requirements.txt<br>

2️⃣ Run the Streamlit App<br>
streamlit run app.py<br>

🛠 Model Details<br>
Model Used: Pre-trained ML Model (model.pkl)<br>
Scaler Used: StandardScaler (scaler.pkl)<br>

Input Features:<br>
Age (Numeric)<br>
Gender (Male → 0, Female → 1)<br>
Tenure (Duration of subscription)<br>
Monthly Recharge (Monthly charge for services)<br>

Prediction Output:<br>
1 → Churn (Customer will leave)<br>
0 → Not Churn (Customer will stay)<br>

🖥️ Web App Demo<br>
🔹 Enter values → Click Predict → Get the prediction result<br>
![App Screenshot](app_screenshot.png)<br>

📜 Dependencies<br>
The app requires the following Python libraries:<br>
1.streamlit<br>
2.joblib<br>
3.numpy<br>
4.Pandas<br>

Install them using:<br>
pip install streamlit joblib numpy<br>
