# 🧠 Predicting Eligibility for NSAP Schemes using Machine Learning

A capstone project developed as part of the **AICTE–Edunet–IBM AI & Cloud Internship**, focused on automating the classification of beneficiaries under the **National Social Assistance Programme (NSAP)** using machine learning techniques. This project aims to enhance the speed, accuracy, and transparency of social welfare distribution.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Problem Statement](#problem-statement)
- [Proposed Solution](#proposed-solution)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [ML Algorithm](#ml-algorithm)
- [Deployment](#deployment)
- [Results](#results)
- [Future Scope](#future-scope)
- [References](#references)

---

## 📝 About the Project

This project leverages **machine learning** to predict the eligibility of citizens for NSAP welfare schemes:
- **IGNOAPS** – Indira Gandhi National Old Age Pension Scheme
- **IGNWPS** – Indira Gandhi National Widow Pension Scheme
- **IGNDPS** – Indira Gandhi National Disability Pension Scheme

Manual allocation is often time-consuming and error-prone. Our system automates this process using demographic and socio-economic data, improving efficiency and reducing misclassification.

---

## ❓ Problem Statement

The NSAP currently uses manual methods to identify eligible beneficiaries, leading to potential delays and misclassification. This project aims to **automate eligibility prediction** using historical and demographic data through machine learning.

---

## ✅ Proposed Solution

The solution includes:
- **Data Collection:** District-wise data from AI_KOSH
- **Preprocessing:** Cleaning, handling missing values, feature engineering
- **Modeling:** Using Random Forest for multi-class classification
- **Deployment:** Cloud-based deployment on IBM Cloud Lite
- **Evaluation:** Accuracy, precision, recall, F1-score, and confusion matrix

---

## ⚙️ Tech Stack

- **Language:** Python 3.x  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib  
- **Cloud Platform:** IBM Cloud Lite  
- **Tools:** IBM Watson Studio, Jupyter Notebook  
- **Version Control:** Git & GitHub

---

## 📂 Dataset

- **Source:** [AI_KOSH – NSAP District-wise Pension Data](https://aikosh.indiaai.gov.in/web/datasets/details/district_wise_pension_data_under_the_national_social_assistance_programme_nsap_1.html)
- **Key Features:**
  - Gender counts (Male/Female/Transgender)
  - Category-wise distribution (SC/ST/OBC/GEN)
  - Aadhaar linkage, mobile number availability
  - Total beneficiaries

---

## 🧠 ML Algorithm

- **Model:** Random Forest Classifier  
- **Preprocessing:** Label encoding, feature selection  
- **Training:** Train-test split and grid search for hyperparameter tuning  
- **Objective:** Predict the suitable NSAP scheme for each record  

---

## ☁️ Deployment

- Hosted on **IBM Cloud Lite**
- Accepts **CSV uploads** or manual input
- Returns the **predicted NSAP scheme code** for each applicant
- Can be extended into a full web-based portal for administrative use

---

## 📊 Results

- The model achieved **high accuracy** in classifying NSAP schemes
- **Reduced manual workload** and improved prediction speed
- **Confusion matrix and feature importance** confirm robust model behavior

---

## 🚀 Future Scope

- Shift from **district-level to individual-level predictions**
- Integrate real-time data from **digital application portals**
- Use advanced models like **XGBoost, LightGBM, or Deep Neural Networks**
- Add **mobile interface** for field usage
- Integrate **Explainable AI (XAI)** and **Edge Computing** for transparency and offline use

---

## 📚 References

- AI_KOSH Dataset – [NSAP Pension Data](https://aikosh.indiaai.gov.in/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio)
- Breiman, L. (2001). *Random Forests*, Springer
- Aggarwal, C. C. (2015). *Data Mining: The Textbook*, Springer
- Witten, I. H. et al. (2016). *Data Mining: Practical Machine Learning Tools and Techniques*, Morgan Kaufmann

---

## 🙋‍♂️ Author

**Bharanieeswaran R**  
B.E. CSE – KPR Institute of Engineering and Technology  
Intern – AICTE–Edunet–IBM AI & Cloud Internship  
GitHub: [@Bharanieeswaran](https://github.com/Bharanieeswaran)  
LinkedIn: [linkedin.com/in/bharanieeswaran-r-08a736310](https://www.linkedin.com/in/bharanieeswaran-r-08a736310/)

---

## 📌 License

This project was created as part of the **AICTE–Edunet–IBM AI & Cloud Virtual Internship 2025**. For academic use only. Contact for collaborations or reuse.
