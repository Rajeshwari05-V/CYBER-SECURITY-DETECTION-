# CYBER-SECURITY-DETECTION-
CYBERSECURITY ATTACK DETECTION USING MACHINE LEARNING ALOGORITHMS
# 🔐 Cybersecurity Attack Detection using Machine Learning

## 📌 Overview

This project presents a **machine learning-based intrusion detection system (IDS)** designed to classify network traffic as **normal or malicious**.
It uses a **large-scale dataset (1M+ records)** and compares multiple ML algorithms to identify the most accurate and scalable solution for cybersecurity threat detection.

The system demonstrates how **ensemble learning techniques significantly outperform traditional models**, achieving accuracy up to **98–99%**.

---

## 🎯 Objectives

* Detect cyber-attacks using machine learning
* Compare multiple classification algorithms
* Minimize false positives and false negatives
* Build a scalable and efficient intrusion detection system

---

## 📊 Dataset

* Large-scale network traffic dataset (1M+ records)
* Features represent system/network behavior
* Target variable:

  * `0 → Normal`
  * `1 → Attack`

---

## ⚙️ Methodology

### 1️⃣ Data Preprocessing

* Missing values handled using **SimpleImputer (mean strategy)**
* Feature scaling using **StandardScaler**
* Dataset sampling for faster computation

### 2️⃣ Data Splitting

* Training Set: 80%
* Testing Set: 20%

### 3️⃣ Models Implemented

* Decision Tree (DTC)
* Random Forest (RFC)
* Gradient Boosting (GBC)
* AdaBoost
* XGBoost (XGB)
* CatBoost
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Multilayer Perceptron (MLP)
* Naïve Bayes (NB)
* Quadratic Discriminant Analysis (QDA)

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall (Sensitivity)
* Specificity
* False Positive Rate (FPR)
* False Negative Rate (FNR)

### Confusion Matrix Components

* True Positive (TP)
* True Negative (TN)
* False Positive (FP)
* False Negative (FN)

---

## 🧠 Key Results

* ✅ Ensemble models (**CatBoost, XGBoost, Random Forest, Gradient Boosting**) achieved **98–99% accuracy**
* ✅ MLP showed strong performance on non-linear data
* ⚠️ Naïve Bayes & QDA had lower accuracy due to assumptions
* ✅ Low False Positive & False Negative rates
* ✅ High True Negative rate → strong normal traffic detection

---

## 📸 Screenshots



![WhatsApp Image 2026-03-30 at 22 11 41](https://github.com/user-attachments/assets/c6a03c88-e248-41fb-83bf-e3339dbbc431)
![WhatsApp Image 2026-03-30 at 22 11 06](https://github.com/user-attachments/assets/475443ed-8b3c-43a0-9171-21dc3959ef89)
![WhatsApp Image 2026-03-30 at 22 09 38](https://github.com/user-attachments/assets/170e2ac3-5899-488a-9384-ce4f04f712e5)
![WhatsApp Image 2026-04-02 at 06 58 23](https://github.com/user-attachments/assets/e0e2eb16-c18d-461d-88dc-aae45d62d499)
![WhatsApp Image 2026-04-02 at 06 58 23 (1)](https://github.com/user-attachments/assets/8fd68376-6450-48cd-bba0-0fd5f001a18a)
![WhatsApp Image 2026-04-02 at 06 58 22](https://github.com/user-attachments/assets/b6e35c93-8798-4602-b2c7-1a9dcb73baf8)
![WhatsApp Image 2026-04-02 at 00 34 20](https://github.com/user-attachments/assets/f78136f4-74ac-4f7a-96a0-6091cb33a1b6)
![WhatsApp Image 2026-04-01 at 23 17 10](https://github.com/user-attachments/assets/fc76c6da-e8ec-4c90-bce2-37500557bcaa)
![WhatsApp Image 2026-04-01 at 23 17 09](https://github.com/user-attachments/assets/94344360-41d2-4079-99ec-fffcf2e9e7c0)
![WhatsApp Image 2026-04-01 at 23 17 08](https://github.com/user-attachments/assets/897b0409-57c1-48b5-86bc-9f34fda54a65)
![WhatsApp Image 2026-03-30 at 22 11 41](https://github.com/user-attachments/assets/cfca45c8-de3d-4c9a-96f8-3db26938a2cf)
<img width="1470" height="956" alt="Screenshot 2026-03-29 at 2 35 59 PM" src="https://github.com/user-attachments/assets/d7fe6a2f-00ae-4e04-ac20-06d4431a81e9" />
<img width="1470" height="956" alt="Screenshot 2026-03-29 at 3 01 25 PM" src="https://github.com/user-attachments/assets/0c945bc6-1055-4e16-8df0-a1051d3b4b0b" />
<img width="1470" height="956" alt="Screenshot 2026-03-29 at 3 13 27 PM" src="https://github.com/user-attachments/assets/8dfad3d3-bd86-4337-ae2c-91073c9a2cf7" />
<img width="1470" height="956" alt="Screenshot 2026-03-30 at 1 14 59 PM" src="https://github.com/user-attachments/assets/a188aaf9-c163-4465-b07b-39674e12f4d6" />



---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* XGBoost, CatBoost
* Matplotlib / Seaborn

---

## 🔮 Future Scope

* Real-time intrusion detection system
* Deep learning models (CNN, RNN)
* Handling class imbalance using SMOTE
* Multi-class attack classification
* Cloud/IoT integration
* Web-based deployment

---

## 📚 References

* Denning, Intrusion Detection Model (1987)
* Breiman, Random Forest (2001)
* Friedman, Gradient Boosting (2001)
* Chen & Guestrin, XGBoost (2016)
* Prokhorenkova et al., CatBoost (2018)

---

## 👩‍💻 Authors

* A. Varsha
* A. Hema Sameera
* C. Akshaya Varma
* Rajeshwari.V

FET, Jain (Deemed-to-be University), Bangalore

---

## ⭐ Conclusion

This project proves that **ensemble machine learning models provide a highly accurate, scalable, and reliable solution for cybersecurity attack detection**, making them suitable for real-world intrusion detection systems.

---
