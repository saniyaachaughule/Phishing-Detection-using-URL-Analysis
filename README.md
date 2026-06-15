# 🛡️ Phishing URL Detection using Machine Learning

## 👤 Developer

**Saniya Chaughule**

---

## 🧠 Project Goal

To develop a machine learning-based web application that detects phishing websites using URL analysis. The system helps users identify suspicious links before visiting potentially harmful websites.

---

## 🔍 Problem Statement

Phishing attacks are one of the most common cybersecurity threats. Attackers create fake websites that imitate trusted organizations to steal sensitive information such as passwords, banking details, and personal data.

Traditional blacklist-based approaches often fail to detect newly created phishing websites. This project uses Machine Learning to analyze URL characteristics and classify URLs as **Phishing** or **Legitimate** in real time.

---

## 💡 Features

✅ User-friendly web interface built with Streamlit

✅ Real-time phishing URL detection

✅ Machine Learning powered prediction

✅ Random Forest Classifier for accurate results

✅ Instant URL analysis

✅ Dark-themed responsive UI

✅ Simple and easy to use

---

## ⚙️ Technologies Used

* **Python 3.11**
* **Streamlit**
* **Scikit-learn**
* **Pandas**
* **NumPy**
* **Joblib**

---

## 📊 Machine Learning Model

### Algorithm Used

**Random Forest Classifier**

### Dataset

Phishing URL Dataset containing legitimate and phishing URLs.

### Workflow

1. Data Collection
2. Feature Extraction
3. Model Training
4. Model Evaluation
5. URL Prediction via Web Interface

---

## 🖥️ Web Application Interface

The user enters a URL into the input field.

Example:

```text
https://google.com/
```

After clicking **"Check URL"**, the system analyzes the URL and displays:

```text
✅ Legitimate URL
```

or

```text
⚠️ Phishing URL
```

---

## 🚀 How to Run the Project

### 1. Clone Repository

```bash
git clone https://github.com/saniyaachaughule/Phishing-Detection-using-URL-Analysis.git

cd Phishing-Detection-using-URL-Analysis
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Train Model (Optional)

```bash
python train_model.py
```

### 4. Run Streamlit Application

```bash
python -m streamlit run app.py
```

### 5. Open Browser

```text
http://localhost:8501
```

---

## 📷 Screenshots

### Home Page

<img width="1919" height="1076" alt="Screenshot 2026-02-26 225242" src="https://github.com/user-attachments/assets/8527f7c1-ccba-46b3-8d90-a3f9173c28ad" />


### Prediction Result

Example:

```text
URL: https://google.com/

Result: Legitimate URL
```

---

## 🔍 How It Works

### Feature Extraction

The system extracts important URL features such as:

* URL Length
* Presence of HTTPS
* Number of Dots
* Special Characters
* Domain Information
* Suspicious URL Patterns

### Prediction

The extracted features are passed to the trained Random Forest model.

### Classification

The model predicts whether the URL is:

* Legitimate
* Phishing

### Output

The result is displayed instantly on the web interface.

---

## 🎯 Applications

* Cybersecurity Awareness
* Safe Web Browsing
* Educational Demonstration
* Phishing Prevention
* Security Research

---

## 🎥 Demo Video

👉 Watch Demo:

[https://youtu.be/xAaTMeI30cI?si=WIquzm39vT4EUyrY](https://youtu.be/xAaTMeI30cI?si=WIquzm39vT4EUyrY)

---

## 📄 License

This project is licensed under the MIT License.

---

## ⚠️ Disclaimer

This project is developed for educational and research purposes only. Predictions may not always be 100% accurate and should not be considered a substitute for professional cybersecurity solutions.

---

## 📚 References

* Scikit-learn Documentation
* Streamlit Documentation
* Kaggle Phishing URL Dataset
* Python Official Documentation

### Changes made:

* Removed **Team Members** section.
* Added **Developer: Saniya Chaughule**.
* Changed **CLI-based tool** to **Streamlit Web Application**.
* Added your new website UI features.
* Updated usage steps to `pyhton -m streamlit run app.py`.
* Added web app workflow and screenshots section.
