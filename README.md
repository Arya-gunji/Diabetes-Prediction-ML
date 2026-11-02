# 🩺 Smart Diabetes Risk Assessment
### Diabetes Prediction Using Machine Learning

## 📌 Project Overview

Smart Diabetes Risk Assessment is a Machine Learning web application that predicts whether a person is likely to have diabetes based on medical input parameters.

The project uses a Random Forest classification model and a Flask web application to provide predictions through a simple and user-friendly interface.

## 🎯 Project Objectives

- Predict diabetes using Machine Learning.
- Perform data preprocessing and handle missing values.
- Apply feature scaling to improve model performance.
- Compare multiple Machine Learning algorithms.
- Build a web application using Flask.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Machine Learning:** Scikit-learn
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib
- **Web Framework:** Flask
- **Frontend:** HTML, CSS
- **Development Tool:** Jupyter Notebook

## 🤖 Machine Learning Algorithms

The following algorithms were implemented and compared:

1. Naive Bayes
2. Random Forest
3. K-Nearest Neighbors (KNN)
4. Support Vector Machine (SVM)

**Selected Model:** Random Forest Classifier

**Reported Accuracy:** 75% (as measured in the project notebook)

## ✨ Features

- Diabetes prediction based on medical parameters.
- Data preprocessing and missing-value handling.
- Feature scaling using StandardScaler.
- Random Forest classification.
- User-friendly web interface.
- Prediction result display.
- Reset button to clear input fields.

## 📸 Project Screenshots

### 1. Home Page
![Smart Diabetes Risk Assessment - Home Page](screenshots/home.png)

### 2. Prediction Result
![Smart Diabetes Risk Assessment - Prediction Result](screenshots/prediction-result.png)

## 📂 Project Structure

```text
Diabetes-Prediction-ML/
│
├── app.py
├── diabetes Model_new_final.ipynb
├── rf_model.pkl
├── scaler.pkl
├── imputer.pkl
├── requirements.txt
├── .gitignore
├── README.md
│
├── templates/
│   └── index.html
│
└── screenshots/
    ├── diabetes-home.png
    └── diabetes-result.png
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Arya-gunji/Diabetes-Prediction-ML.git
```

### 2. Open the Project Folder

```bash
cd Diabetes-Prediction-ML
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Flask Application

```bash
python app.py
```

### 5. Open in Browser

```text
http://127.0.0.1:5000/
```

## 🔄 Application Workflow

1. User enters the required medical details.
2. Flask receives the input values.
3. The imputer handles missing values.
4. The scaler transforms the input data.
5. The Random Forest model predicts the result.
6. The prediction is displayed on the web page.

## 📊 Model Performance

The Random Forest model achieved **75% accuracy** in the reported notebook evaluation.

The notebook also includes model comparison using accuracy, confusion matrix, and classification report.

## 👨‍💻 Developer

**Arya Gunji**

- GitHub: https://github.com/Arya-gunji
- LinkedIn: https://www.linkedin.com/in/arya-gunji/

## ⚠️ Disclaimer

This project is developed for educational purposes only. Its predictions are not a medical diagnosis. Please consult a qualified healthcare professional for medical advice.

---

⭐ If you find this project useful, feel free to explore the repository!
