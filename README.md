# 🏦 Customer Churn Prediction Web Application  

This project is a **machine learning-based web app** designed to predict whether a banking customer is likely to churn (i.e., leave the bank). By leveraging customer data such as age, balance, and geography, the application delivers real-time churn predictions through a clean and easy-to-use web interface.  

---

## 📌 Key Features  
- 🔮 Predicts customer churn using a pre-trained **ML model**.  
- 🖥️ Interactive **web interface** for entering customer details.  
- ⚡ Built with **Flask** for lightweight and fast deployment.  
- 📊 Model trained and saved with **Scikit-learn & Pickle** for reusability.  

---

## 🛠 Technologies Used  
- **Python 3**  
- **Flask** – For web framework and routing  
- **Scikit-learn** – For training the machine learning model  
- **Pickle** – For model serialization and loading  
- **HTML/CSS** – For frontend UI (stored inside `templates/`)  

---

## 🧠 Model Information  
- **Algorithm:** Random Forest Classifier  
- **Input Features:**  
  - Credit Score  
  - Age  
  - Tenure  
  - Balance  
  - Number of Products  
  - Has Credit Card (0 or 1)  
  - Is Active Member (0 or 1)  
  - Estimated Salary  
  - Geography (France, Spain, Germany → One-hot encoded)  
  - Gender (Male/Female → Binary encoded)  

- **Output Prediction:**  
  - **1** → Customer is likely to churn  
  - **0** → Customer is likely to stay  

---

## 📂 Project Structure  
Customer-Churn-Management-app/ ├── templates/ │ ├── index.html # Web interface template for input and prediction │ ├── app.py # Flask application file
