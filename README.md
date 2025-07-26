# 🩺 Diabetes Prediction System

This project uses machine learning to predict whether a person is diabetic or not based on health parameters such as glucose level, BMI, age, blood pressure, etc.

## 🚀 Features
- Trained using the Pima Indians Diabetes Dataset
- Achieves high accuracy on test data
- Built with Python, Pandas, Scikit-learn
- Easy-to-use Streamlit web interface

## 📁 Project Structure
├── Diabetes_Prediction.ipynb # Model training and evaluation
├── diabetes.csv # Dataset used
├── app.py # Streamlit web app
├── requirements.txt # Python dependencies
└── README.md # Project documentation


## 🧠 Model Performance
- **Training Accuracy**: ~87%
- **Testing Accuracy**: ~76%
- Uses XGBoost Model

## 🖥️ Streamlit App
Input values for:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

Get instant prediction output: **Diabetic** or **Not Diabetic**

## 🛠️ How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
