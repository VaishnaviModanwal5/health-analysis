# health-analysis

#  Exploratory Data Analysis of Gym Members Dataset

##  Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on the **Gym Members Exercise Tracking Dataset**.

The analysis was performed to understand patterns, trends, and relationships between different health and fitness-related features.

---

##  Author
**Vaishnavi Modanwal**

---

##  Objective
The main objectives of this project are:

- To explore and understand the dataset
- To visualize the data using graphs
- To identify patterns and trends
- To analyze relationships between variables

---

##  Dataset Description
The dataset contains information about gym members, including:

- Age
- Gender
- Weight
- Height
- BMI
- Calories Burned
- Workout Type
- Session Duration
- Heart Rate (Avg_BPM, Resting_BPM)
- Fat Percentage
- Water Intake
- Workout Frequency
- Experience Level

---

##  Data Cleaning Steps
The following data cleaning steps were performed:

- Removed duplicate records
- Handled missing values
- Filled numeric missing values using median
- Filled categorical missing values using mode
- Cleaned column names
- Removed basic outliers (IQR method)

---

##  Visualizations Used
Different types of graphs were used:

- ✅ Histograms → To see distributions
- ✅ Boxplots → To detect outliers
- ✅ Bar Charts → To compare categories
- ✅ Pie Charts → To show proportions
- ✅ Line Charts → To see trends
- ✅ Heatmap → To analyze correlations
- ✅ Waffle Chart → To show category distribution

---

##  Tools & Libraries
The project was implemented using:

- Python
- Pandas
- Matplotlib
- Seaborn
- PyWaffle

---

## Key Insights
Some important observations:

- Members belong to different age groups
- Calories burned increases with session duration
- BMI and Fat Percentage show correlation
- Workout habits vary across members
- Heart rate varies with workout intensity

---

## Conclusion
EDA helped in understanding the dataset, identifying trends, detecting outliers, and visualizing relationships between features.

This project demonstrates how data visualization helps interpret health and fitness data easily.

---

##  Future Improvements
Possible enhancements:

- Add Machine Learning model
- Build interactive dashboard
- Add recommendation system
- Perform deeper statistical analysis

---

##  Project Files
- `gym_members_exercise_tracking_synthetic_data.csv`
- `eda_analysis.py`
- `cleaned_health_data.csv`
- `README.md`

---

##  How to Run

1. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn pywaffle
