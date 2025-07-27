# Multiple Disease Prediction System

This is a web application that allows users to predict the likelihood of having:
- Diabetes
- Heart Disease
- Parkinson’s Disease

The predictions are made using pre-trained machine learning models.

---

## 🚀 Features

- Interactive web UI built with Streamlit
- Upload and enter patient data manually
- Real-time disease prediction
- Uses models trained with `scikit-learn`
- Option menu for selecting diseases
- Intuitive interface with sidebar navigation

---

## 🧰 Tech Stack

- Python 3
- Streamlit
- scikit-learn
- pandas, numpy
- pickle (for loading models)
- streamlit-option-menu

---

## 📁 Project Structure
📦your_project/
┣ 📜app.py
┣ 📜diabetes_trained_model.pkl
┣ 📜heart_trained_model.pkl
┣ 📜parkinson_trained_model.pkl

---

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/health-diagnosis-app.git
cd health-diagnosis-app
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```
4. Running the App
```bash
streamlit run app.py
```
