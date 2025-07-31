# 🔥 Classification of Fire Types in India Using MODIS Satellite Data (2021–2023)

## 📌 Project Overview  
This project focuses on **classifying fire types in India** (such as forest fires, agricultural burning, and other thermal anomalies) using **MODIS satellite data** obtained from NASA’s FIRMS (Fire Information for Resource Management System) for the years **2021–2023**.  

The project applies **data preprocessing, exploratory data analysis (EDA), visualization, and machine learning models** to predict fire types accurately. The **Random Forest Classifier** was selected as the best-performing model.  

---

## 🎯 Objectives  
- Classify different fire types in India using satellite data.  
- Identify fire-prone regions and patterns over time.  
- Build a machine learning pipeline for predictive analysis.  
- Support environmental monitoring and disaster management efforts.  

---

## 🛠️ Technologies Used  
- **Programming Language:** Python  
- **Libraries & Tools:**  
  - Data Processing: `numpy`, `pandas`  
  - Visualization: `matplotlib`, `seaborn`, `folium`  
  - Machine Learning: `scikit-learn`, `xgboost`  
  - Model Evaluation: `classification_report`, `ConfusionMatrixDisplay`  

---

## 📂 Dataset Details  

- **Satellites:** Terra (AM) & Aqua (PM)  
- **Period Covered:** January 2021 – December 2023  
- **Data Size:** 2.7 lakh+ fire detection records  
- **Key Features:**  
  - `latitude`, `longitude` – Location of fire detection  
  - `brightness` – Fire pixel temperature  
  - `frp` – Fire Radiative Power  
  - `confidence` – Confidence score of fire detection  
  - `type` – Fire type classification label  

## Screen shorts of project
<img width="1918" height="1031" alt="streamlit app ss" src="https://github.com/user-attachments/assets/9d06c079-b0e7-4de6-85dc-557f0ec13ace" />
<img width="1918" height="842" alt="streamlit_output" src="https://github.com/user-attachments/assets/98a16f08-6a24-4e30-9288-4374f536620c" />


## 📊 Exploratory Data Analysis (EDA)  
- **Distribution Analysis:** Countplot of fire types, day/night observations, and satellite data.  
- **Statistical Analysis:** Outlier detection using boxplots, summary statistics.  
- **Geospatial Visualization:** Folium maps showing fire hotspots across India.  
- **Correlation Heatmap:** Identifying relationships among brightness, FRP, and confidence.  

---

## 🤖 Machine Learning Models Tested  
- **Logistic Regression** – Baseline model, low performance for non-linear patterns.  
- **Decision Tree** – Captured non-linear relationships but prone to overfitting.  
- **Random Forest (Selected Model)** – Best accuracy, robust to noise, good generalization.  
- **K-Nearest Neighbors (KNN)** – Performance affected by dataset size.  
- **XGBoost** – Good accuracy but more complex to tune.  

---

## ✅ Final Model Selection  
- **Model Chosen:** Random Forest Classifier  
- **Reason:**  
  - Best accuracy and F1-score across fire types  
  - Robust against outliers and imbalance  
  - Provided feature importance for better interpretability  

---

## 📌 Results & Insights  
- Brightness, FRP, and confidence were the most important features for classification.  
- Random Forest model achieved **high accuracy** in predicting fire types.  
- Identified key fire hotspots in India during 2021–2023.  
- Balanced detection during day and night observations.  

---

## 🚀 Future Scope  
- **Real-Time API Integration:** Connect with NASA FIRMS live feed for real-time predictions.  
- **Interactive Dashboard:** Deploy using Flask/Django/Streamlit for hotspot visualization.  
- **Deep Learning Models:** Explore CNN/LSTM architectures for enhanced accuracy.  

---

## 📜 Author  
**Umesh Saini**  
- 🎓 BE-CSE, Chandigarh University  
- 🔗 [LinkedIn](https://linkedin.com) | [GitHub](https://github.com)  
