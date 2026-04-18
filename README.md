# 🚀 ML Preprocessing Assignment

## 📌 Overview

This assignment focuses on preparing a small passenger dataset for machine learning by applying **categorical encoding** and **feature scaling** techniques.

---

## 📊 Dataset Details

The dataset contains the following features:

* Gender 👤
* City 🌆
* Size 📦
* Age 🎂
* Fare 💰

---

## 🧠 Tasks Performed

### 🔠 Categorical Encoding

* **Gender** → Label Encoding (Male/Female converted to 0/1)
* **City** → One-Hot Encoding (avoiding dummy variable trap)
* **Size** → Ordered encoding (Small=0, Medium=1, Large=2)

---

### ⚖️ Feature Scaling

* Applied **RobustScaler** on Age and Fare
* Reason: Fare contains an outlier (450), and RobustScaler handles outliers effectively using median and IQR

---

## 🛠️ Tools & Libraries

* Python 🐍
* Pandas 📊
* Scikit-learn 🤖
* Google Colab ☁️

---

## 📁 Project Structure

* `ML-Preprocessing-Assignment` → Main notebook with complete solution

---

## ▶️ How to Run

1. Open the notebook in Google Colab
2. Run all cells step-by-step
3. Ensure no errors occur

---

## 📌 Submission

* Uploaded on GitHub
* Public repository link submitted via course portal

---

## 👨‍🎓 Author

**Keshav Kaushik**

B.Sc Computer Science (IInd Year)

---

✨ This project demonstrates basic data preprocessing techniques used in machine learning, including categorical encoding and feature scaling. The dataset is transformed using Label Encoding, One-Hot Encoding, and RobustScaler to make it suitable for model training.
  
