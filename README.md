# 📊 Medical Appointment No-Show Analysis

This project explores a real-world dataset of medical appointments from Brazil to find out **why some patients do not show up** for their scheduled appointments. The goal is to understand patterns using data analysis and visualizations.

## 🧠 Project Objective

To analyze the factors that affect whether a patient **shows up or misses** their medical appointment. This includes studying features like:
- Age
- Gender
- SMS reminders
- Scholarship (free healthcare)
- Day of the week, etc.

## 📁 Dataset Info

- 📌 **Source**: Kaggle (Medical Appointment No-Shows)  
- 🧾 **Rows**: ~110,000 patient appointments  
- 📋 **Columns**: 14 features including appointment date, gender, age, and more.

## 🧰 Tools & Libraries Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook

## 🔍 Steps Performed

1. **Data Loading & Overview**  
   - Loaded the CSV file and checked the shape and data types.

2. **Data Cleaning**  
   - Renamed columns to make them easier to work with.  
   - Removed incorrect or missing data (like negative ages).  
   - Converted dates into proper formats.

3. **Exploratory Data Analysis (EDA)**  
   - Checked the distribution of patients who showed up vs. no-shows.  
   - Analyzed the impact of age, gender, day of the week, and SMS reminders.  
   - Used visualizations like bar charts, histograms, and box plots.

4. **Key Insights**  
   - Younger patients were more likely to miss appointments.  
   - Patients who received an SMS reminder were more likely to show up.  
   - Certain weekdays had higher no-show rates.

## 📈 Sample Visualizations

- Bar plots comparing show/no-show by gender and age groups  
- Histograms showing age distribution  
- Heatmaps to explore feature correlations

## 🧩 What I Learned

- How to clean and prepare real-world datasets  
- How to use Pandas and Seaborn for analysis and visualization  
- How to find useful patterns that can help solve a real problem

## ✅ Future Improvements

- Build a predictive model to **predict no-shows** in advance  
- Create an interactive dashboard using **Power BI** or **Tableau**


---

