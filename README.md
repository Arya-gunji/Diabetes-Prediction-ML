# 🩺 Smart Diabetes Risk Assessment

### Machine Learning Based Diabetes Prediction System

## 📌 Project Overview

This project predicts whether a person is diabetic or not using Machine Learning algorithms. It also provides a Flask web application where users can enter health-related details and receive a prediction.

The application uses a trained Random Forest model to generate predictions based on patient health information.

## 🎯 Project Objectives

- Predict diabetes using Machine Learning.
- Perform data preprocessing and feature scaling.
- Compare different classification algorithms.
- Develop a user-friendly web application using Flask.

## 🛠️ Technologies Used

- Python
- Machine Learning
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Flask
- HTML
- CSS
- Jupyter Notebook

## 🤖 Machine Learning Algorithms

- Naive Bayes
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

**Selected Model:** Random Forest

## ✨ Features

- Patient health information input form.
- Diabetes prediction using Random Forest.
- Data preprocessing.
- Missing value handling using SimpleImputer.
- Feature scaling using StandardScaler.
- Attractive blue gradient background.
- Medical icon and input field icons.
- Green and red prediction result indicators.
- Reset button to clear input fields.
- Responsive user interface.
- About Project section.
- Developer profile with GitHub and LinkedIn links.

## 📊 Model Performance

Random Forest achieved **75% accuracy** in the notebook's reported results.

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
│
└── templates/
    └── index.html
```

## ⚙️ How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Arya-gunji/Diabetes-Prediction-ML.git
```

### 2. Navigate to Project Folder

```bash
cd Diabetes-Prediction-ML
```

### 3. Install Dependencies

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

1. User enters patient health information.
2. Flask receives the input through the prediction form.
3. Missing values are handled using the saved imputer.
4. Input features are scaled using the saved scaler.
5. Random Forest model generates the prediction.
6. The result is displayed on the webpage.

## 👨‍💻 Developer

**Arya Gunji**

- GitHub: [Arya-gunji](https://github.com/Arya-gunji)
- LinkedIn: [Arya Gunji](https://www.linkedin.com/in/arya-gunji/)

## ⚠️ Disclaimer

This project is developed for educational purposes only. Its predictions are not a substitute for professional medical advice or diagnosis.

---

⭐ If you find this project useful, feel free to explore the repository!
