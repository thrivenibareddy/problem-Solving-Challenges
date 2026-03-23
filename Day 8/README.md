# 🚚 Logistics Performance Dashboard 

## 📊 Overview
This project presents a Power BI dashboard designed to analyze logistics and delivery performance. It helps track on-time deliveries, delays, costs, and regional efficiency.


## 🎯 Objective
To analyze delivery performance across regions and cities, identify delays, and provide actionable insights to improve logistics operations.


## 📁 Dataset
The dataset contains shipment-level details such as:
- Shipment ID
- Order Date & Delivery Date
- Expected Delivery Date
- Origin & Destination Cities
- Region (North, South, East, West)
- Distance (km)
- Delivery Cost (USD)
- Delivery Status (On-time, Delayed, Cancelled)
- Delivery Time (Days)


## 📌 Key KPIs
- Total Shipments
- On-Time Delivery %
- Average Delivery Time (Days)
- Total Delivery Cost
- Delayed Shipments
  

## 📈 Dashboard Features
- 📊 KPI Cards for quick insights
- 🌍 City-wise delivery performance (matrix/heatmap)
- 📉 Avg delivery time by region (bar chart)
- 🚚 Shipment delay analysis
- 🎯 Filters for Region, City, and Delivery Status


## 🧮 DAX Measures Used
- On-Time Delivery %
  
     OnTime Delivery % = divide(calculate(COUNTROWS(logistics_data),logistics_data[DeliveryDate]<=logistics_data[ExpectedDate]),countrows(logistics_data))
  
- Total Shipments
  
    Total Shipments = COUNT(logistics_data[ShipmentID])
  
- Avg Delivery Time
  
     Avg Delivery Time = AVERAGE(logistics_data[DeliveryTime_Days])
  
- Total Cost
  
     Total Delivery Cost = SUM(logistics_data[Cost_USD])
  
- Delay Analysis
  
    Delayed Shipments = CALCULATE(COUNT(logistics_data[ShipmentID]),'logistics_data'[DeliveryStatus]="Delayed")



## 💡 Key Insights
- Certain regions show higher delivery delays
- Delivery cost increases with distance
- Some cities consistently underperform
- Delays greater than 2 days indicate operational inefficiencies


## 🛠 Tools Used
- Power BI
- DAX (Data Analysis Expressions)
  

