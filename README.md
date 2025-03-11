# Titanic_Dataset_Python_EDA
Titanic Dataset - Exploratory Data Analysis (EDA) 🚢
🔹 Project Overview
This project performs Exploratory Data Analysis (EDA) on the Titanic dataset from Kaggle using NumPy, Pandas, and Matplotlib. The goal is to uncover insights about passenger survival based on various factors such as gender, class, age, fare, family size, and embarkation port.

📌 Key Features & Insights
✅ Basic Data Exploration: Checked missing values, unique values, and summary statistics.
✅ Data Cleaning & Handling Missing Values:

Filled missing ages with the median.
Filled missing embarkation port with the most frequent value.
Dropped Cabin column due to excessive missing data.
✅ Feature Engineering for New Insights:
Created Age Groups (Child, Teen, Adult, etc.).
Extracted Titles (Mr., Miss, etc.) from passenger names.
Identified passengers who traveled alone vs. with family.
✅ Survival Rate Analysis Based on Different Factors:
Gender: Higher survival rate for females.
Class: First-class passengers had a better survival chance.
Fare Price: Higher fares correlated with better survival.
Family Size: Traveling with family increased survival chances.
✅ Data Visualization with Matplotlib:
Bar Charts: Survival rate by gender, class, and embarkation port.
Histograms: Age distribution of passengers.
Box Plots: Fare distribution for survivors vs. non-survivors.
Line Plots: Impact of family size on survival.
🛠️ Tech Stack
Python 🐍
Pandas (for data manipulation)
NumPy (for numerical computations)
Matplotlib (for data visualization)
📊 Results & Findings
🚀 Females had a higher survival rate (~74%) compared to males (~18%)
🚀 First-class passengers had the highest survival rate (~62%)
🚀 Passengers traveling alone had lower survival chances
🚀 Passengers who paid higher fares had better survival rates
