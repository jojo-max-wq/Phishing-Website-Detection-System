# Phishing-Website-Detection-System
Phishing is a cyberattack where fake websites mimic trusted platforms to steal sensitive data like passwords and banking details. This system uses machine learning to analyze URL patterns and detect suspicious features, helping users identify potentially harmful websites before sharing personal information.


# 🛡️ Phishing Website Detection System

A Machine Learning-powered web application that detects phishing websites by analyzing URL patterns and structural characteristics. This system helps users identify potentially malicious websites before sharing sensitive information.

---

## 📖 Project Overview

Phishing attacks are one of the most common cybersecurity threats, where attackers create fraudulent websites that mimic legitimate platforms to steal user credentials, banking details, and personal data.

This project implements a supervised machine learning model trained on labeled URL data to classify websites as:

- ✅ Legitimate  
- ⚠️ Phishing  

The trained model is deployed using a Flask web application that allows users to input URLs and receive instant predictions.

---

## 🚀 Key Features

- 🔍 URL-based phishing detection  
- 🤖 Machine Learning classification model  
- 🌐 Interactive web interface  
- ⚡ Real-time predictions  
- 📊 Trained on labeled phishing dataset  
- 🧪 Jupyter Notebook for experimentation and model training  

---

## 🛠️ Tech Stack

### Backend
- Python  
- Flask  

### Machine Learning
- Scikit-learn  
- Pandas  
- NumPy  

### Frontend
- HTML5  
- Tailwind CSS  
- Bootstrap  

### Dataset
- `phishing_site_urls.csv` (labeled phishing & legitimate URLs)

---

## 🧠 Machine Learning Workflow

1. **Data Collection** – Labeled dataset of phishing and legitimate URLs  
2. **Data Preprocessing** – Cleaning and formatting URL data  
3. **Feature Extraction** – Structural and lexical URL analysis  
4. **Model Training** – Supervised classification model  
5. **Evaluation** – Performance validation  
6. **Deployment** – Integration into Flask web app  

Model experimentation and training are documented in:
        Phishing Website detection system.ipynb


---

## 📂 Project Structure
Phishing-Website-Detection/
│
├── app.py                                 # Flask application
├── index.html                             # Frontend UI
├── phishing_site_urls.csv                 # Dataset
├── Phishing Website detection system.ipynb
├── README.md




---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

git clone https://github.com/your-username/phishing-website-detection.git
cd phishing-website-detection


## Create Virtual Environment (Recommended)

python -m venv venv
source venv/bin/activate      # Mac/Linux
venv\Scripts\activate         # Windows

##Install Dependencies
pip install flask pandas numpy scikit-learn

##Running the Application
Start the Flask server: python app.py
Open your browser and navigate to: http://127.0.0.1:5000/

Enter a URL to check whether it is phishing or legitimate.


## 🖥️ Application Workflow

1. User inputs a URL  
2. URL features are extracted  
3. The trained ML model predicts classification  
4. Result is displayed instantly on the webpage  




