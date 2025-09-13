# 🏥 Healthcare EDA with Python

This project explores **healthcare data** using **Python**. It focuses on data cleaning, exploratory data analysis (EDA), and visualization to uncover insights about patient records and healthcare trends.

## 📌 Project Overview
- Data Cleaning (handling missing values, duplicates, etc.)
- Exploratory Data Analysis (EDA) with Pandas & NumPy
- Visualizations using Matplotlib & Seaborn
- Insights & Recommendations based on the dataset

## 📂 Files in this Repository
- `Healthcare EDA Data Analysis with Python.ipynb` → Main Jupyter Notebook
- `HealthcareRawData.csv` → Dataset used
- `README.md` → Project documentation

## 📊 Key Findings

- 👩 **Gender**: Female patients booked more appointments compared to male patients.  
- 👶 **Age Groups**: Show/no-show ratios are almost equal across age groups, except for **Age 0 and Age 1**, where the show rate is **~80%**.  
- 🏘 **Neighbourhoods**: Most neighbourhoods recorded a consistent **~80% show rate**.  
- 🎓 **Scholarship**:  
  - 99,666 patients without a scholarship → ~80% showed up.  
  - 21,801 patients with a scholarship → ~75% showed up.  
- ❤️ **Hypertension**:  
  - 88,726 patients without hypertension → ~78% showed up.  
  - 21,801 patients with hypertension → ~85% showed up.  
- 💉 **Diabetes**:  
  - 102,584 patients without diabetes → ~80% showed up.  
  - 7,943 patients with diabetes → ~83% showed up.  
- 📩 **SMS Reminder**:  
  - 75,045 patients who did **not** receive SMS → ~84% showed up.  
  - 35,482 patients who received SMS → only ~72% showed up.  
- 📅 **Day of the Week**:  
  - **No appointments on Sunday**.  
  - **Very few on Saturday** compared to weekdays.  

---

## ⚙️ Technologies Used
- Python (Anaconda Distribution)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/python-bender/Health_care_Eda_with_Python-.git
