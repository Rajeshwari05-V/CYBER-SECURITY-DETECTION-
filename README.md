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
