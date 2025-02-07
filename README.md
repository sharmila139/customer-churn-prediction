# customer-churn-prediction
# **Customer Churn Prediction App **  
_A machine learning-powered web app to predict customer churn using Streamlit and TensorFlow._  

##  **Overview**  
This project is a **Streamlit-based web application** that predicts whether a customer is likely to churn based on various features like credit score, balance, number of products, and more. The model is trained using **TensorFlow & Scikit-learn**, and the app is deployed on **Streamlit Cloud / Render**.  

## **Features**  
- User-friendly **Streamlit UI**  
- Real-time customer churn prediction**  
- Pre-trained deep learning model** using `TensorFlow`  
- Uses **OneHotEncoding & LabelEncoding** for categorical data  
- **Scales input features** with `StandardScaler`  
- Easily deployable on **Streamlit Cloud / Render / AWS**  

## **Project Structure**  
```
📺 customer-churn-app
│── app.py                 # Main Streamlit app
│── model.h5               # Trained TensorFlow model
│── scaler.pkl             # StandardScaler object
│── label_encoder_gender.pkl   # LabelEncoder for Gender
│── onehot_encoder_geo.pkl     # OneHotEncoder for Geography
│── requirements.txt       # Dependencies list
│── README.md              # Project documentation
```

## **How to Run Locally**  
### **Step 1: Clone the Repository**  
```bash
git clone https://github.com/YOUR_USERNAME/customer-churn-app.git
cd customer-churn-app
```
### **Step 2: Install Dependencies**  
```bash
pip install -r requirements.txt
```
### **Step 3: Run the App**  
```bash
streamlit run app.py
```

## **Live Demo**  
👉**[Try the App Here](https://your-deployed-app-url)**  

## **Contributing**  
Feel free to open issues or submit pull requests! 🚀  

---

