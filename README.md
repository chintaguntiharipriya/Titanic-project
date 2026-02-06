# 🚢 Titanic Data Analysis – Case Study

This project presents a complete exploratory data analysis (EDA) of the classic **Titanic dataset** using Python. The objective is to understand passenger demographics, survival patterns, and key factors that influenced survival on the Titanic.

---

## 📌 Project Description

The Titanic dataset is a widely used dataset for data analysis and machine learning.  
In this project, we perform data cleaning, preprocessing, and analysis to uncover insights such as:

- Survival based on gender, class, and age  
- Passenger distributions  
- Fare comparisons  
- Deck-wise passenger distribution  
- Embarkation analysis  

This case study uses **Seaborn's built-in Titanic dataset**, and demonstrates analytical skills suitable for portfolios, GitHub, and data analyst profiles.

---

## ✅ Key Features

- Loading and exploring Titanic dataset  
- Handling missing values (Age, Embarked, Deck, Embark_Town)  
- Data cleaning and type conversion  
- Group-by analysis for survival, demographics, and location  
- Statistical insights  
- Clear interpretation of results  
- Based on real historical event analysis  

---

## 🛠 Tech Stack / Tools Used

- **Python**
- **Pandas**
- **NumPy**
- **Seaborn**
- **Matplotlib**
- **Google Colab / Jupyter Notebook**

---

## 📁 Folder Structure

Titanic-Case-Study/
│
├── Titanic cs.collab.ipynb
├── Titanic cs.collab.pdf
├── images/ (optional visualizations)
└── README.md

yaml
Copy code

---

## 🔧 Data Cleaning Steps

### ✔️ Missing Values Treated
- **Age** → Replaced with mean  
- **Embarked** → Replaced with mode  
- **Deck** → Replaced with mode  
- **Embark_Town** → Replaced with mode  

### ✔️ Data Type Fixes
- Converted *Age* to integer  
- Verified data types using `df.info()`

Dataset after cleaning contains:  
**891 passengers × 15 columns**

---

## 📊 Exploratory Data Analysis (Important Outputs)

### 👥 Total Passengers  
**891**

### 👩‍🦰👨 Gender Distribution  
- **Male:** 577  
- **Female:** 314  

### ❤️ Total Survived  
**342 out of 891**

### 👩‍🦰 Female vs Male Survival  
- **Females survived:** 233  
- **Males survived:** 109  

### 🌍 Survival by Embarkation Port
- **Southampton:** 219  
- **Cherbourg:** 93  
- **Queenstown:** 30  

### 🛏 Deck Distribution  
- Most passengers were on **Deck C (747)**  
- Least: Deck G (4)

### 👨‍👩‍👦 SibSp (Siblings/Spouses on board)
Most passengers traveled **alone (SibSp = 0 → 608)**

### 💰 Average Fare by Class
| Class | Average Fare |
|-------|---------------|
| 1     | 84.15         |
| 2     | 20.66         |
| 3     | 13.68         |

---

## 📌 Insights

- **Women were prioritized in rescue**, resulting in significantly higher survival.
- **First-class passengers** paid much more and had better chances of survival.
- **Deck C** held the highest number of passengers, showing uneven cabin distribution.
- More passengers traveled **alone (537)** compared to family travelers.
- Most survivors came from **Southampton**, likely due to more total passengers boarding there.

---

## 📝 Recommendations

- Improve **safety equity**—survival chances should not depend on ticket class.
- Provide **clear safety communication**, especially for passengers traveling alone.
- Modernize evacuation protocols to prioritize **children and vulnerable groups**.
- Ensure balanced cabin distribution across decks to prevent overcrowding.

---

## ▶️ How to Run This Project

1. Install required libraries:
```bash
pip install pandas numpy seaborn matplotlib
Run the notebook:

bash
Copy code
jupyter notebook
Open:

nginx
Copy code
Titanic cs.collab.ipynb

AUTHOR
NAME: HARIPRIYA
EMAIL-chintaguntiharipriya@gmail.com
