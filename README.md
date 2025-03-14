# NOAA Temperature Analysis (2005-2015)


## 📌 Overview
This project analyzes NOAA temperature records from **2005 to 2015**, focusing on **record highs, record lows, and 2015 anomalies**.

## 📊 Dataset Information
- `temperature.csv`: Contains daily temperature records.
- `BinSize.csv`: Provides location data for weather stations.

# 🔍 Analysis & Logical Implementation

### **1️⃣ Data Preprocessing**
- **Convert Date Column** → Ensure proper date format (`datetime` conversion).
- **Remove Leap Days (Feb 29)** → Maintains consistency across years.
- **Extract Year & Day of Year** → Helps in trend analysis.

### **2️⃣ Temperature Trends (2005-2014)**
- **Compute Record Highs/Lows** → Find the highest & lowest temperatures for each day.
- **Plot High/Low Trends** → A line graph with shaded regions for clarity.

### **3️⃣ Identifying Record-Breaking Days (2015)**
- **Compare 2015 Data with Historical Records** → Identify anomalies.
- **Mark Record-Breaking Days on the Graph** → Uses scatter points for visualization.

### **4️⃣ Weather Station Map Visualization**
- **Use GeoPandas for Mapping** → Helps plot station locations.
- **Highlight Stations Near Ann Arbor, Michigan** → Focus on a specific region.

### **5️⃣ Temperature Summary (2015)**
- **Calculate Daily Averages** → Shows how 2015 compares to historical data.
- **Visualize Ann Arbor Trends** → Provides localized insights.

## 🚀 Dependencies
This project requires:
- `pandas` → Data manipulation.
- `matplotlib` & `seaborn` → Data visualization.
-  folium →  interactive map visualizations
