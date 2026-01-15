# 📌 Placement Prediction System (Machine Learning + Flask)
 Live Demo: https://pp-guoi.onrender.com/


## Project Overview
This project is an **end-to-end machine learning application** that predicts whether a student is likely to be **placed or not** based on two academic indicators:
- **CGPA**
- **IQ score**

The system demonstrates the **complete ML lifecycle**:
data preprocessing → model training → evaluation → model serialization → web deployment using Flask.

---

## Problem Statement
Educational institutions and students often want an early indicator of placement probability.
This project provides a **binary classification solution** to help analyze placement outcomes using historical student data.

---

## Tech Stack
- **Programming Language:** Python  
- **Machine Learning:** Scikit-learn (Logistic Regression)  
- **Data Analysis:** NumPy, Pandas  
- **Visualization:** Matplotlib, Seaborn  
- **Web Framework:** Flask  
- **Model Serialization:** Joblib  
- **Frontend:** HTML, CSS  

---

## Project Structure
├── app.py # Flask application
├── index.html # Frontend UI
├── placement.ipynb # Data analysis & model training
├── placement.csv # Dataset
├── place.pkl # Trained ML model
└── README.md # Project documentation


---

## Dataset Description
The dataset contains **100 student records** with the following features:

| Feature   | Description |
|----------|------------|
| CGPA     | Cumulative Grade Point Average |
| IQ       | Intelligence Quotient score |
| Placement| Target variable (1 = Placed, 0 = Not Placed) |

---

## Machine Learning Model
- **Algorithm:** Logistic Regression  
- **Train-Test Split:** 80% / 20%  
- **Task Type:** Binary Classification  

### Model Performance
- **Accuracy:** **85%**
- **Evaluation Metric:** Accuracy Score

The trained model is serialized using **Joblib** for reuse in the Flask application.

---

## Web Application
A simple and user-friendly web interface allows users to:
1. Enter **IQ** and **CGPA**
2. Submit the form
3. Instantly receive a prediction:
   - **Placed**
   - **Not Placed**

---

##  How to Run Locally

### Clone the Repository
```bash
1. git clone https://github.com/<your-username>/<repository-name>.git
2. cd <repository-name>
3. pip install -r requirements.txt
4. python app.py
5. http://127.0.0.1:5000/


## Key Learning Outcomes

--Built a binary classification ML model
--Understood feature selection & model evaluation
--Deployed a trained ML model using Flask
--Integrated ML inference with a web interface
--Applied industry-standard ML workflow

## Future Improvements

--Add more features (communication skills, internships, projects)
--Use advanced models (Random Forest, XGBoost)
--Add model explainability (SHAP / feature importance)
--Improve UI and validation handling

👨‍💻 Author
Mr.Sajan kumar Sah
B.Tech CSE | Minor in Applied Machine Learning
Aspiring Machine Learning Engineer

📄 License
This project is open-source and available for educational purposes.
