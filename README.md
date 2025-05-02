# 🛡️ Phishing URL Detection using Machine Learning

This project is developed as part of the Cybersecurity Internship organized by **Digisuraksha Parhari Foundation** and powered by **Infinisec Technologies Pvt. Ltd.**

## 📌 Problem Statement

Phishing attacks are among the most common cybersecurity threats today. They trick users into revealing sensitive information by impersonating legitimate websites. This project aims to detect whether a given URL is **legitimate** or **phishing** using basic URL-based features and a machine learning model.

---

## 🎯 Objective

To build a lightweight, CLI-based cybersecurity tool that:
- Analyzes URLs
- Extracts structural features
- Predicts phishing threats using Random Forest Classifier

---

## 🛠️ Setup Instructions

### 🔧 Prerequisites
- Python 3.7+
- `pip` installed

### 🧪 Installation Steps

```bash
git clone https://github.com/your-username/phishing-url-detector.git
cd phishing-url-detector/tool

# Install dependencies
pip install -r requirements.txt

# Prepare dataset features
python prepare_dataset.py

# Train the model
python train_model.py

# Test a URL
python predict_cli.py
