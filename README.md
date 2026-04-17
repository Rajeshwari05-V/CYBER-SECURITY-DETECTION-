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

#CAT BOOST

test_size = 0.2
<img width="1470" height="956" alt="Screenshot 2026-04-10 at 6 23 10 PM" src="https://github.com/user-attachments/assets/60a94382-3065-4225-865f-775c9574a83a" />


test_size = 0.4
<img width="1470" height="956" alt="Screenshot 2026-04-10 at 6 24 58 PM" src="https://github.com/user-attachments/assets/e098e707-0346-4cc2-bb75-36698422a438" />


test_size = 0.6
<img width="1470" height="956" alt="Screenshot 2026-04-10 at 6 25 55 PM" src="https://github.com/user-attachments/assets/b24e3800-86c0-4d22-8606-9b40610aa455" />




#DTC

test_size = 0.2
<img width="1470" height="956" alt="Screenshot 2026-04-10 at 6 27 10 PM" src="https://github.com/user-attachments/assets/d3b248c0-25e2-4b02-a399-6a85419ee7fa" />


test_size = 0.4
<img width="1470" height="956" alt="Screenshot 2026-04-10 at 6 28 11 PM" src="https://github.com/user-attachments/assets/910b0edd-8072-4b31-8aca-cc06d57a0e4e" />


test_size = 0.6
<img width="1470" height="956" alt="Screenshot 2026-04-10 at 6 28 51 PM" src="https://github.com/user-attachments/assets/cfe65862-1498-4426-96fc-6acf8281b000" />






#GBC

test_size = 0.2
<img width="1470" height="956" alt="Screenshot 2026-04-10 at 6 32 31 PM" src="https://github.com/user-attachments/assets/90aab2f3-f7fc-4024-b7ec-9a1db52f8551" />


test_size = 0.4
<img width="1470" height="956" alt="Screenshot 2026-04-10 at 6 35 00 PM" src="https://github.com/user-attachments/assets/2e5b4ce2-fa51-4530-9496-1caa3f34d37d" />


test_size = 0.6
<img width="1470" height="956" alt="Screenshot 2026-04-10 at 6 36 28 PM" src="https://github.com/user-attachments/assets/cee3d06f-544f-41ab-9c19-cf5a4734bc66" />





#KNEIGHBOUR CLASSIFIER

test_size = 0.2
<img width="1470" height="956" alt="Screenshot 2026-04-10 at 6 37 28 PM" src="https://github.com/user-attachments/assets/556974fe-a1bc-4b08-aa6b-9a80c16506e9" />



test_size = 0.4
<img width="1470" height="956" alt="Screenshot 2026-04-10 at 6 48 35 PM" src="https://github.com/user-attachments/assets/19dee6b2-291b-4c00-857b-0399ad00a5ec" />


test_size = 0.6
<img width="1470" height="956" alt="Screenshot 2026-04-10 at 6 47 17 PM" src="https://github.com/user-attachments/assets/41d60494-affa-4817-bd99-aab6df25e0ff" />



#SVM

test_size = 0.2
<img width="1600" height="900" alt="WhatsApp Image 2026-04-02 at 00 34 21" src="https://github.com/user-attachments/assets/ba2af9cb-fda2-4ac2-a3d8-0086428de61a" />


test_size = 0.4
<img width="1600" height="900" alt="WhatsApp Image 2026-04-02 at 00 34 21 (1)" src="https://github.com/user-attachments/assets/7cd7bdca-f533-4dd8-8d8b-08b2cfe6f1cf" />


test_size = 0.6
<img width="1600" height="900" alt="WhatsApp Image 2026-04-02 at 00 34 20" src="https://github.com/user-attachments/assets/e232f8b3-a563-42e5-a6b7-055cdc863609" />



#LDA

test_size = 0.2
<img width="1600" height="853" alt="WhatsApp Image 2026-04-02 at 06 58 22" src="https://github.com/user-attachments/assets/ab290833-6a24-4cca-a36c-13199917d6a4" />



test_size = 0.4
<img width="1600" height="854" alt="WhatsApp Image 2026-04-02 at 06 58 22 (2)" src="https://github.com/user-attachments/assets/a9d8dbb5-bb2a-492a-ab4e-2ee03e80b5a7" />



test_size = 0.6
<img width="1600" height="852" alt="WhatsApp Image 2026-04-02 at 06 58 22 (3)" src="https://github.com/user-attachments/assets/39a6d94e-b25a-4e72-9aa4-7ae58eba3763" />






#LG

test_size = 0.2
<img width="1600" height="900" alt="WhatsApp Image 2026-04-02 at 00 34 21" src="https://github.com/user-attachments/assets/30e3ced1-ae1b-4f62-ba09-1d612458ebb8" />
<img width="1600" height="852" alt="WhatsApp Image 2026-04-02 at 06 58 23 (2)" src="https://github.com/user-attachments/assets/e111175a-74d0-4b85-8215-4823039112c0" />


test_size = 0.4
<img width="1600" height="850" alt="WhatsApp Image 2026-04-02 at 06 58 23 (3)" src="https://github.com/user-attachments/assets/417420fe-fb55-440f-a2ad-232bedb9498a" />


test_size = 0.6
<img width="1600" height="851" alt="WhatsApp Image 2026-04-02 at 06 58 23 (4)" src="https://github.com/user-attachments/assets/716273f7-77d6-43a2-9571-e52e2dc620b5" />






#LGBM

test_size = 0.2<img width="1600" height="852" alt="WhatsApp Image 2026-04-02 at 06 58 23 (5)" src="https://github.com/user-attachments/assets/19ac4183-a920-42a0-9b8a-4bbb6f0422f4" />


test_size = 0.4
<img width="1600" height="852" alt="WhatsApp Image 2026-04-02 at 06 58 24" src="https://github.com/user-attachments/assets/7c631076-84d9-40ee-bd5b-b2abf9e823f9" />


test_size = 0.6
<img width="1600" height="852" alt="WhatsApp Image 2026-04-02 at 06 58 24 (1)" src="https://github.com/user-attachments/assets/c85febba-9c43-4df5-8920-68ce25353c67" />






#SVM

test_size = 0.2
<img width="1600" height="900" alt="WhatsApp Image 2026-04-02 at 00 34 21" src="https://github.com/user-attachments/assets/75afa096-463a-4cf8-bebc-499efb59ef25" />


test_size = 0.4
<img width="1600" height="900" alt="WhatsApp Image 2026-04-02 at 00 34 21 (1)" src="https://github.com/user-attachments/assets/6ab4b137-93b2-42d4-b444-04515eb5f985" />



test_size = 0.6
<img width="1600" height="900" alt="WhatsApp Image 2026-04-02 at 00 34 20" src="https://github.com/user-attachments/assets/bcc475e4-acb4-479f-9fe7-d8c2a61714f4" />





#MLP

test_size = 0.2
<img width="1600" height="900" alt="WhatsApp Image 2026-04-02 at 00 34 19" src="https://github.com/user-attachments/assets/fb402ae2-3dd7-40cf-8d6d-ae195520f351" />


test_size = 0.4
<img width="1600" height="900" alt="WhatsApp Image 2026-04-02 at 00 34 19 (1)" src="https://github.com/user-attachments/assets/8db04f7a-c43b-4b53-89d4-9b8065212455" />

test_size = 0.6
<img width="1600" height="900" alt="WhatsApp Image 2026-04-02 at 00 34 18" src="https://github.com/user-attachments/assets/cbcd8ecd-3d37-4f21-bde5-65c3d22762d9" />




#NB

test_size = 0.2
<img width="1600" height="900" alt="WhatsApp Image 2026-04-02 at 00 34 20 (2)" src="https://github.com/user-attachments/assets/d8aab803-a3e5-41c3-9172-43dbd149e181" />



test_size = 0.4
<img width="1600" height="900" alt="WhatsApp Image 2026-04-02 at 00 34 20 (3)" src="https://github.com/user-attachments/assets/8d5375d3-7d45-4b08-9bdc-aa8543334843" />


test_size = 0.6
<img width="1600" height="900" alt="WhatsApp Image 2026-04-02 at 00 34 20 (1)" src="https://github.com/user-attachments/assets/4fd35a7e-1272-4066-9b94-c9f07683c11b" />






#QDA

test_size = 0.2
<img width="1600" height="901" alt="WhatsApp Image 2026-04-01 at 23 17 11" src="https://github.com/user-attachments/assets/1c3d4894-c5ac-4922-9b85-562b9b5d9893" />


test_size = 0.4
<img width="1600" height="900" alt="WhatsApp Image 2026-04-01 at 23 17 10 (3)" src="https://github.com/user-attachments/assets/94e46049-6c33-4d42-95e0-75e924fbbd95" />

test_size = 0.6
<img width="1600" height="907" alt="WhatsApp Image 2026-04-01 at 23 17 10" src="https://github.com/user-attachments/assets/ef49477f-3967-4aac-b08a-0060ebce47ea" />




#RFC

test_size = 0.2
<img width="1600" height="945" alt="WhatsApp Image 2026-03-30 at 22 11 42" src="https://github.com/user-attachments/assets/1a719e4e-afd2-41e2-a75b-3c089a8119c5" />


test_size = 0.4

<img width="1600" height="829" alt="WhatsApp Image 2026-03-30 at 22 10 26" src="https://github.com/user-attachments/assets/e5dacae6-ca89-463c-8e90-a81dc1ea8935" />


test_size = 0.6
<img width="1600" height="823" alt="WhatsApp Image 2026-03-30 at 22 10 56" src="https://github.com/user-attachments/assets/1fbac812-c6a6-4009-a73a-39e83f08d7a3" />





#XGB

test_size = 0.2
<img width="1600" height="825" alt="WhatsApp Image 2026-03-30 at 22 11 06" src="https://github.com/user-attachments/assets/5b8a1fb4-7cad-40b8-b6ca-9bbd8cf99ef2" />


test_size = 0.4
<img width="1600" height="826" alt="WhatsApp Image 2026-03-30 at 22 11 11" src="https://github.com/user-attachments/assets/403bd31f-a9fa-4300-a955-fc4487cd39d8" />


test_size = 0.6
<img width="1600" height="827" alt="WhatsApp Image 2026-03-30 at 22 11 22" src="https://github.com/user-attachments/assets/4d9cf367-b11d-45c2-99c7-39601a43938f" />






#ADA BOOSTCLASSIFIER


test_size = 0.2
<img width="1600" height="956" alt="WhatsApp Image 2026-03-30 at 22 11 41" src="https://github.com/user-attachments/assets/fd711761-809f-44ad-8cdd-b7e17683880f" />


test_size = 0.4
<img width="1600" height="943" alt="WhatsApp Image 2026-03-30 at 22 11 41 (2)" src="https://github.com/user-attachments/assets/c1895c2c-52fc-4e17-9100-9f3fb9112b8a" />


test_size = 0.6
<img width="1600" height="945" alt="WhatsApp Image 2026-03-30 at 22 11 42" src="https://github.com/user-attachments/assets/ee82deed-1702-48b7-8dfe-80834b969a35" />




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
