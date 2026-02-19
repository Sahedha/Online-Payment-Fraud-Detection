# 💳 Online Payment Fraud Detection System

🚀 **Live Demo:**  
👉 https://online-payment-fraud-detection-app.onrender.com/

---

## 📌 Project Overview

This project is a Machine Learning–based web application that detects whether an online transaction is **fraudulent or legitimate** using a trained classification model and a premium responsive UI.

The model is trained on a real-world dataset and deployed using Flask on a cloud server.

---

## 🛠️ Technologies Used

- Python
- Machine Learning (Scikit-learn)
- Data Analysis (Pandas, NumPy)
- Flask Web Framework
- Bootstrap UI
- Model Deployment (Render)

---

This project demonstrates the complete ML pipeline:

✔ Data preprocessing  
✔ Model training  
✔ Model evaluation  
✔ Model serialization  
✔ Flask web deployment  
✔ Responsive front-end UI  
✔ Real-time prediction  

---

## 🚀 Features

- 🔍 Real-time fraud prediction  
- 🧠 Machine Learning powered detection  
- 💎 Premium responsive UI  
- 📱 Mobile-friendly design  
- ⚡ Fast predictions  
- 🖥️ Clean user interface  

---

## 🧠 Problem Statement

Online payment fraud is increasing rapidly. Manual detection is inefficient and slow.

This system uses Machine Learning to analyze transaction details and predict whether a transaction is fraudulent.

---

## 📊 Machine Learning Model

- Algorithm: **Random Forest Classifier**
- Type: Supervised Classification
- Output:  
  - ✅ Legitimate Transaction  
  - ⚠ Fraudulent Transaction  

---

## 📥 Input Features Used

The model uses the following transaction details:

| Feature | Description |
|----------|-------------|
| `step` | Time step of transaction |
| `type` | Encoded transaction type |
| `amount` | Transaction amount |
| `oldbalanceOrg` | Sender balance before transaction |
| `newbalanceOrig` | Sender balance after transaction |
| `oldbalanceDest` | Receiver balance before transaction |
| `newbalanceDest` | Receiver balance after transaction |
| `isFlaggedFraud` | System flagged fraud indicator |

---

## 🏗️ Project Structure

```
Online_Payment_Fraud_Detection_Project/
│
├── app.py                      # Main Flask application
├── payments.pkl                # Trained ML model
├── requirements.txt            # Project dependencies
├── README.md                   # Documentation
│
├── templates/                  # HTML templates
│   ├── home.html               # Homepage
│   ├── predict.html            # Input form page
│   └── result.html             # Prediction result page
│
├── static/                     # Static assets
│
├── training/                   # Model training files
│   └── fraud_model_training.ipynb
│
└── dataset/                    # Dataset folder (optional)
    └── dataset.csv
```



---

## 📂 Dataset

This project uses the PaySim synthetic financial dataset.

🔗 Download Dataset:  
https://www.kaggle.com/datasets/ealaxi/paysim1

Note: Dataset is not included in this repository due to GitHub file size limits.

---

## 🧪 Model Training Steps

1. Data cleaning and preprocessing  
2. Encoding categorical features  
3. Feature selection  
4. Train-test split  
5. Training Random Forest model  
6. Model evaluation  
7. Saving model using Pickle  

---

## 💾 Model Saving

The trained model is saved as:

payments.pkl


---

## 🖥️ How to Run the Project Locally

### ✅ Step 1 — Clone the Repository

git clone https://github.com/Sahedha/Online-Payment-Fraud-Detection.git


---

### ✅ Step 2 — Create Virtual Environment

python -m venv venv


Activate:

**Windows :**
venv\Scripts\activate


**Mac/Linux :**
source venv/bin/activate


---

### ✅ Step 3 — Install Dependencies

pip install -r requirements.txt


---

### ✅ Step 4 — Ensure Model File Exists

Make sure this file is in the project root:

payments.pkl


---

### ✅ Step 5 — Run the Flask Application

python app.py


---

### ✅ Step 6 — Open in Browser

Go to:

http://127.0.0.1:5000


---

## 📸 Application Workflow

1. User opens homepage  
2. Navigates to prediction page  
3. Enters transaction details  
4. Model processes input  
5. Result page displays fraud status  

---

## 📱 UI Features

- Premium modern design  
- Glassmorphism effect  
- Background image layout  
- Responsive on mobile & desktop  
- Interactive buttons  
- Clean form layout  

---

## 🔐 Sample Test Inputs

### ✅ Legitimate Transaction Example

Step: 1
Type: 2
Amount: 5000
Old Balance Origin: 20000
New Balance Origin: 15000
Old Balance Dest: 0
New Balance Dest: 5000
Flagged Fraud: 0(no)


---

### ⚠ Fraudulent Transaction Example

Step: 10
Type: 2
Amount: 750000
Old Balance Origin: 750000
New Balance Origin: 0
Old Balance Dest: 0
New Balance Dest: 750000
Flagged Fraud: 1(yes)


---

## 🚀 Future Improvements
 
- Add user authentication  
- Real-time transaction monitoring  
- Model optimization  
- API integration  
- Dashboard analytics  

---

## 👩‍💻 Author

**Sahedha Shaik**  
B.Tech Final Year Student  

---

## ⭐ If you found this project useful, consider giving it a star!
