# Shooting Incident Fatality Analysis

This project analyzes historical NYPD shooting incident data to explore trends and build a machine learning model that classifies whether a shooting incident is fatal or non-fatal. The goal is to assist law enforcement agencies with data-driven insights for targeted policing strategies.

---

## 📂 Project Structure

- Data loading and cleaning
- Feature engineering (time encoding, categorical handling)
- Exploratory Data Analysis (EDA)
- Model training and evaluation
- Final insights and conclusion

---

## 📊 Dataset

- Source: NYPD Shooting Incident Data (Historic)
- Key features:
  - Date and Time of occurrence
  - Borough and precinct
  - Location descriptors
  - Victim and perpetrator demographics
  - Fatality flag

---

## ⚙️ Features Engineered

- Time-based features (sine/cosine encoding for Hour, Month, Day of Week)
- Dropped irrelevant columns (incident key, some null-heavy location descriptors)
- Cleaned and imputed null values in perpetrator-related fields

---

## 🧠 Model Training

*The model section will include the classification model used (like Logistic Regression, Random Forest, etc.), evaluation metrics, and performance scores.*

---

## 📈 Results

*Summarize EDA insights and classification results (like accuracy, recall, etc.).*

---

## 📌 Requirements

```bash
pandas
numpy
scikit-learn
matplotlib
seaborn




