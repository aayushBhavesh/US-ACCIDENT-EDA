# 🚗 US Accidents Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project presents a comprehensive **Exploratory Data Analysis (EDA)** on a large-scale **US Accidents dataset containing over 7 million records**.  
The objective is to analyze accident patterns across **time, geography, and data sources**, assess data quality, and derive meaningful insights before applying any advanced modeling techniques.

The analysis is designed to be **scalable, reproducible, and performance-aware**, reflecting real-world data analytics practices.

---

## 🗂 Dataset Description
- **Dataset Size:** 7+ million accident records  
- **Geographic Scope:** United States 🇺🇸  
- **Data Type:** Road accident data collected from multiple sources  

### 🔑 Key Features Used
- `Start_Time` – Accident occurrence timestamp  
- `Source` – Data provider  
- `State`, `City` – Geographic identifiers  
- `Start_Lat`, `Start_Lng` – Location coordinates  
- `Severity` – Accident severity level (where available)  

> ⚠️ **Note:** Due to its large size, the full dataset is not included in this repository.

---

## 📥 Dataset Access
The dataset can be downloaded from the original source:

🔗 **US Accidents Dataset (Kaggle)**  
https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

---

## 🎯 Project Objectives
- Perform structured EDA on a large real-world dataset  
- Identify **temporal patterns** (hourly, weekday vs weekend)  
- Analyze **spatial concentration** across cities and states  
- Evaluate **source-wise and year-wise data availability**  
- Assess **data quality and missing values**  
- Generate clear and reproducible analytical outputs  

---

## 🔍 Analysis Performed
- Data cleaning and validation  
- Source × Year data availability analysis  
- Hourly and day-wise accident trend analysis  
- Weekend vs weekday comparison  
- Top cities and states by accident count  
- Geospatial hotspot analysis using interactive heatmaps  
- Missing value and data quality assessment  

---

## 💡 Key Insights
- Accident occurrence is strongly influenced by **time of day and day of week**  
- **Weekdays and commuting hours** pose higher accident risk  
- Accident data is **spatially concentrated**, not evenly distributed  
- A small number of cities and states contribute a large share of accidents  
- Data availability varies across sources and years  
- Data quality assessment is essential before drawing conclusions  

---

## ⚠️ Limitations
- The analysis is **descriptive** and does not establish causality  
- Some source–year combinations contain no data  
- Certain features have high missing values  
- Spatial analysis is based on sampled data for performance reasons  

---

## 🛠 Tools and Technologies
- **Python**  
- **Pandas, NumPy**  
- **Matplotlib, Seaborn**  
- **Folium (Interactive Maps)**  
- **Jupyter Notebook / VS Code**  

---

## 📁 Project Structure
├── notebooks/
│ └── eda_us_accidents.ipynb
├── eda_plots/
│ └── *.png
├── eda_maps/
│ └── *.html
├── data/
│ └── sample_us_accidents.csv (optional)
├── .gitignore
├── README.md
├── LICENSE


---

## 🧾 Conclusion
This project demonstrates a structured and scalable approach to exploratory data analysis on a real-world, large-volume dataset. The insights derived from temporal and spatial analysis provide a strong foundation for future work such as **predictive modeling, severity analysis, and traffic risk assessment**, while emphasizing the importance of data validation and thoughtful exploration.

---

## 👤 Author
**Aayush Shah**  

---

## 📄 License
This project is licensed under the **MIT License**.
