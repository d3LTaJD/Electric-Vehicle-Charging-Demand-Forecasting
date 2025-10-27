# ⚡ Electric Vehicle Charging Demand Forecasting

## 🧩 Objective
To forecast electricity demand at EV charging stations using historical usage, weather, and temporal data.  
The project helps optimize energy distribution, reduce congestion, and enhance operational efficiency.

---

## 🧰 Tools Used
- **Python** – Data cleaning, feature engineering, and model building  
- **Excel** – Preliminary data exploration and formatting  
- **Tableau** – Visualization of demand heatmaps and time-based trends  

---

## 📁 Dataset Description
The project merges two datasets:
1. **EV Usage Data** – Hourly energy consumption, timestamps, and station details  
2. **Weather Data** – Temperature, humidity, precipitation, and wind speed  

---

## 🧠 Steps to Build the Project
1. **Data Preprocessing**
   - Merged EV usage and weather datasets on timestamps  
   - Handled missing values and outliers  
   - Extracted time features (hour, weekday, holiday, etc.)

2. **Model Development**
   - Built time-series forecasting models (ARIMA and Prophet)  
   - Added external regressors (temperature, precipitation)  
   - Evaluated performance using MAE and RMSE metrics  

3. **Visualization (in Tableau)**
   - Imported the final forecast CSV into Tableau  
   - Created **heatmaps** showing demand by **hour and day**  
   - Built **line charts** for trend analysis over time  
   - Added filters for temperature, precipitation, and holidays  

---

## 🎨 How to Create a Heatmap in Tableau
1. Open Tableau → Connect → Text File → Load your forecast CSV  
2. Drag:
   - `Day_of_Week` → Columns  
   - `Hour_of_Day` → Rows  
   - `Predicted_Demand_kWh` → Color  
3. Edit color scale (e.g., Red–Blue diverging)  
4. Add filters like **Temperature** or **Holiday** for interactivity  
5. Combine the heatmap and line chart into a **dashboard**

---

## 📊 Deliverables
- Trained forecasting model (Prophet/ARIMA)  
- Tableau heatmaps and dashboards  
- Charging optimization insights for energy management  

---

## ✅ Conclusion
This project provides a data-driven approach to manage EV charging infrastructure efficiently.  
By integrating time-series forecasting with weather and temporal data, it helps predict demand patterns, ensuring balanced energy distribution and reduced grid stress.

