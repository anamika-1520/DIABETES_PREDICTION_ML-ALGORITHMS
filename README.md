# 🩺 Diabetes Prediction using Machine Learning

A machine learning web application that predicts whether a person is likely to have diabetes based on medical diagnostic measures like glucose level, BMI, insulin, age, and more.

---

## 📸 Demo
![App Screenshot](images/demo.png)

*(Upload a screenshot or Streamlit demo GIF of your app here.)*

---

## 🚀 Features

- Predicts diabetes using user input (Glucose, BMI, Insulin, Age, etc.)
- Supports multiple ML algorithms:  
  ✅ Logistic Regression  
  ✅ Random Forest  
  ✅ K-Nearest Neighbors  
  ✅ Support Vector Machine  
- Clean and interactive UI using Streamlit
- Model evaluation with accuracy, confusion matrix, and classification report
- Easy-to-use form-based interface

---

## 📁 Dataset Used

- **Dataset Name**: Pima Indians Diabetes Dataset  
- **Source**: [Kaggle – Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)  
- **Attributes**:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
  - Outcome (0 = No Diabetes, 1 = Diabetes)

---

## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Streamlit

---

## 🔧 Installation

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/diabetes-predictor.git
cd diabetes-predictor

# 2. Create virtual environment (optional)
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
streamlit run app.py

