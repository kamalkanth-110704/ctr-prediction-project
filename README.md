# Click-Through Rate (CTR) Prediction

## 📖 Overview
This project predicts whether a user will click on an online advertisement using machine learning models.  
It is a classification problem where the target variable is **`Clicked on Ad`** (0 = No, 1 = Yes).

---

## 🎯 Objective
- Understand user behavior towards online advertisements.
- Compare different machine learning models (Logistic Regression, Decision Tree, Random Forest).
- Help advertisers target the right audience and optimize ad spending.

---

## 📂 Dataset
The dataset contains **10,000 records** with the following features:
- **Daily Time Spent on Site** → Time spent by user (minutes).  
- **Age** → User’s age.  
- **Area Income** → Average income of the user’s region.  
- **Daily Internet Usage** → Time spent online daily.  
- **Ad Topic Line** → Advertisement text.  
- **City, Country, Gender** → Demographics.  
- **Clicked on Ad** → Target (0 or 1).  

👉 Dataset file: `ad_10000records.csv`

---

## 🔧 Tech Stack
- **Python**  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
- Jupyter Notebook / Google Colab  

---

## 📊 Workflow
1. Data Preprocessing  
   - Handle categorical variables (Gender, City, Country).  
   - Feature selection for model training.  

2. Exploratory Data Analysis (EDA)  
   - Correlation heatmaps.  
   - Trends between age, internet usage, and ad clicks.  

3. Model Training  
   - Logistic Regression  
   - Decision Tree Classifier  
   - Random Forest Classifier  

4. Evaluation  
   - Accuracy Score  
   - Classification Report (Precision, Recall, F1)  
   - Confusion Matrix  

---

## 🚀 Results
- Logistic Regression → ~90% accuracy  
- Decision Tree → ~94% accuracy  
- Random Forest → ~96% accuracy (Best Model ✅)

---

## 📌 Future Work
- Add more features (time of day, device type, etc.).  
- Deploy model as a **Flask / Django web app**.  
- Create an **interactive dashboard** with Streamlit or Power BI.  
- Try deep learning (ANNs).  

---

## 📂 Project Structure
ctr-prediction-project/
│
├── ad_10000records.csv # Dataset
├── click_through_rate_prediction.ipynb # Jupyter Notebook
├── main.py # (Optional) Python script version
└── README.md # Project documentation


---

## ✨ Author
(Kamal Kanth Silla)**  

