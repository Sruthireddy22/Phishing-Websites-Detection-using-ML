# Phishing-Websites-Detection-using-ML
A Machine Learning-based project to detect phishing websites by analyzing various URL and domain-based attributes. This project uses feature engineering and classification techniques to distinguish between legitimate and phishing websites with high accuracy.

📌 Table of Contents
Abstract

Tech Stack

System Architecture

Features

Model Performance

Screenshots

Testing

Conclusion

Contributors

📄 Abstract
Phishing is a form of cyberattack where fraudulent websites impersonate legitimate ones to steal user credentials or distribute malware. This project aims to counteract such threats using a machine learning approach. By applying the Gradient Boosting Classifier and feature selection techniques, this system accurately identifies phishing attempts based on data attributes—without needing actual URLs.

💻 Tech Stack
Languages & Libraries:

Python

Pandas, NumPy

Scikit-learn (ML Models)

Matplotlib (Visualization)

Flask (Web Framework)

Tools:

Jupyter Notebook / VS Code

HTML/CSS (for UI)

Kaggle Dataset / PhishTank Dataset

🏗️ System Architecture
Data Collection

Data Preprocessing

Feature Extraction

Model Training (Gradient Boosting)

Prediction System

Web Interface for User Input

🔍 Features
Gradient Boosting Classifier for phishing detection

Achieves 97.4% accuracy on test data

Wrapper-based feature selection

Real-time prediction system via Flask

Detects phishing websites using domain-level data attributes

Robust against new phishing websites (no dependency on blacklists)

📊 Model Performance
Training Accuracy: 98.9%

Test Accuracy: 97.4%

F1 Score (Test): 0.977

Precision (Test): 0.966

Recall (Test): 0.989

🖼️ Screenshots
Login Page

Upload Dataset

Prediction Result

Performance Metrics Visualization

✅ Testing
Unit Tests:

Validates individual modules like login, input checking, and URL prediction.

Integration Testing:

Ensures components like data processing, model prediction, and user input interface work together correctly.

System Testing:

Full functionality testing on realistic inputs.

Acceptance Testing:

Verifies that the system behaves as expected in real-world scenarios.
How to Run
# Clone this repo
git clone https://github.com/Sruthireddy22/Phishing-Websites-Detection-using-ML.git
cd Detection of Phishing Websites

# Install dependencies
pip install -r REQUIREMENTS.pdf

# Run the app
python app.py

🧠 Conclusion
This machine learning-based system effectively addresses phishing website detection with high accuracy and minimal false positives. By analyzing features rather than relying on blacklists, it adapts better to newly emerging phishing methods.

👥 Contributors
Thurupu Sruthi – 21BF1A05G8

Thupakula Venkatesh – 21BF1A05G6

Muppalla Keerthana – 22BF5A0516

Guide: Mrs. S. Rajeswari (Assistant Professor)
