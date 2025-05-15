# 📊 Customer Churn Prediction

An interactive **machine learning web application** built using **Streamlit** that predicts whether a customer will churn (i.e., leave the bank) based on their profile information. This project uses a trained deep learning model with preprocessed inputs for predictions.

---

## 🌐 Live App

👉 **Try it out here**: [Customer Churn Prediction App](https://customer-churn-prediction-l3wrh79uua4aswjraestse.streamlit.app/)

---

## 🧠 Project Overview

Churn prediction is a critical issue in the banking and telecom industries. Retaining existing customers is far less costly than acquiring new ones. This project predicts customer churn using deep learning and provides:

- A user-friendly interface
- Encoded inputs with preprocessing
- Visual and tabular inputs for clarity

---

## 🗃 Dataset Information

The dataset used is `Churn_Modelling.csv`, which contains 10,000 records of customers from a bank. Each record includes:

- **CreditScore**
- **Geography**
- **Gender**
- **Age**
- **Tenure**
- **Balance**
- **Number of Products**
- **Has Credit Card**
- **Is Active Member**
- **Estimated Salary**
- **Exited (Target Label)**

---

## 🔍 Technologies Used

- **Frontend**: Streamlit
- **Backend Model**: Keras (TensorFlow)
- **Preprocessing**: Scikit-learn
- **Deployment**: Streamlit Cloud

---

## 🏗 Project Structure

├── app.py # Streamlit app interface

├── prediction.ipynb # Notebook to demonstrate predictions

├── experiments.ipynb # Model training and testing

├── model.h5 # Trained deep learning model

├── label_encoder_gender.pkl # Label encoder for gender feature

├── onehot_encoder_geo.pkl # One-hot encoder for geography

├── scaler.pkl # Feature scaling transformer

├── Churn_Modelling.csv # Raw dataset

├── requirements.txt # Python dependencies

├── runtime.txt # Python version config for deployment

├── LICENSE # Project license (MIT)

└── README.md # Project documentation

## 💻 Getting Started Locally

### 1. Clone the Repository


git clone https://github.com/shinewithsachin/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction

### 2. Set Up the Environment
pip install -r requirements.txt

### 3. Run the Streamlit App
streamlit run app.py

## 🧪 Model Details

Architecture: Deep Neural Network

Framework: TensorFlow/Keras

Evaluation Metrics: Accuracy, Precision, Recall

Encoders:
-label_encoder_gender.pkl

-onehot_encoder_geo.pkl

Scaler:
-scaler.pkl

## 📷 Screenshots
![Input-Output](assets/screenshot.png)


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


