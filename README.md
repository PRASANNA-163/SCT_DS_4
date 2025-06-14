# 🚦 Traffic Accident Analysis (Task 4 - SkillCraft Internship)

This project aims to analyze large-scale traffic accident data to uncover patterns related to **time of day**, **weather**, **road conditions**, and **location hotspots**. Built as part of **Task 4** in my **Data Science Internship at SkillCraft Technology**.

---

## 📌 Objective

- Identify when (time/day) and where (city/region) traffic accidents are most frequent.
- Understand how weather conditions and visibility affect accident severity.
- Visualize hotspots using geographic heatmaps.
- Provide actionable business insights based on data patterns.

---

## 📂 Dataset

The dataset used is the **[U.S. Accidents (2016–2021)](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents)** from Kaggle.

- 📦 **Size:** ~1.3 GB (~2.8 million rows)
- ⚠️ **Note:** Due to GitHub file size limitations, the full dataset is not included in this repository.  
  Please [download the dataset here](https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents) and place it in the project root directory :


---

## 📊 Features Explored

- **Start_Time**: Timestamp of the accident
- **Severity**: 1 to 4 scale of accident severity
- **Weather_Condition**, **Visibility**, **Temperature**, etc.
- **Location**: City, State, Latitude, Longitude

---

## 🧠 Key Insights

- Most accidents occur during **Afternoon and Evening**
- Accidents peak around **8 AM and 5 PM** (rush hours)
- **Clear weather** sees the highest number of accidents (exposure bias)
- Slightly higher severity during **night-time**
- Urban regions show high-density **hotspots**

---

## 📈 Visualizations Included

- Bar Charts: Top weather conditions, days of week
- Line Charts: Hourly accident trend
- Pie Charts: Severity distribution
- Combo Chart: Accident count + Avg severity by time of day
- 🌍 Heatmap: Accident hotspot visualization (Folium + Latitude/Longitude)
- Interactive Dashboards: Built using `plotly`

---

## 🧰 Technologies Used

- `pandas`, `numpy` – data manipulation  
- `matplotlib`, `seaborn` – static charts  
- `plotly` – interactive visualizations  
- `folium` – geo heatmaps  
- `Jupyter Notebook / Python 3.10+`

---
