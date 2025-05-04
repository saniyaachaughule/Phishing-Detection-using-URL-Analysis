## 🛡️ Phishing URL Detection using Machine Learning

## 👥 Team Members
- **Saniya Santosh Choughule**
- **Iqra Mohd Nisar Khan**

## 🧠 Project Goal
To develop a machine learning-based tool that can detect phishing websites using only the URL. This helps in preventing users from falling victim to fraudulent sites.

---

## 🔍 Problem Statement

Phishing is a deceptive technique used by attackers to trick individuals into providing sensitive data by impersonating trusted websites. These fake websites are commonly distributed via URLs that look legitimate. Manual detection is difficult, and traditional blacklists often fail to detect new phishing links. Our tool provides a machine-learning-based approach to analyze and detect phishing URLs dynamically.

---

## 💡 Features

- Input a URL and get instant prediction (Phishing or Legitimate)
- Trained on a real-world dataset of labeled URLs
- Random Forest classifier for reliable detection
- Simple CLI-based tool
- Cleanly structured Python code

---

## ⚙️ Technologies Used

- **Python 3.11** – Core programming language
- **Scikit-learn** – For training the machine learning model
- **Pandas** – For data manipulation and analysis
- **Joblib** – For saving and loading the trained model

---
## 🧪 How to Use
```bash
### 1. Clone this Repository

git clone https://github.com/saniyaachaughule/Phishing-Detection-using-URL-Analysis
cd Phishing-Detection-using-URL-Analysis

### 2. Set Up Environment

python -m venv phishing-env
phishing-env\Scripts\activate  # On Windows
pip install -r requirements.txt

### 3. Train the Model

cd tool/source_code
python train_model.py

### 4. Run URL Prediction

python predict_cli.py
```

## 📊 Screenshots & outputs / Architecture Diagram

Enter a URL to check: https://google.com/

Result: Legitimate

![image](https://github.com/user-attachments/assets/8bb42e88-126b-46b5-9b94-a8d376c5bbc1)

---

## 🎥 Demo Video
👉 Watch on YouTube (replace with actual link)

---

## 📄 License
This project is for educational purposes only under the MIT License.

---

## ⚠️ Disclaimer
This tool is a demonstration of ML-based detection and is not a replacement for enterprise-grade threat protection solutions.

---

## 📚 References
Scikit-learn Docs

Phishing Dataset (Kaggle)

---
