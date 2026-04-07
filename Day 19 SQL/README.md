# 🌾 Farmers Database Management System

## 📌 Project Overview

This project is a **SQL-based database system** designed to manage agricultural operations. It includes data on farmers, land plots, crop yields, and irrigation usage, and provides analytical queries for insights.

---

## 🗂️ Database Schema

### 👨‍🌾 Farmers

Stores farmer details:

* `farmer_id` (Primary Key)
* `first_name`
* `last_name`
* `email`
* `hire_date`

### 🌱 Plots

Stores plot and crop details:

* `plot_id` (Primary Key)
* `plot_name`
* `farmer_id` (Foreign Key)
* `crop_type`
* `soil_type`

### 🌾 Yields

Stores harvest data:

* `yield_id` (Primary Key)
* `plot_id` (Foreign Key)
* `harvest_date`
* `yield_kg`
* `weather_condition`

### 💧 Irrigation Logs

Stores irrigation details:

* `log_id` (Primary Key)
* `plot_id` (Foreign Key)
* `irrigation_date`
* `water_amount_liters`

---

## 🔗 Relationships

* One farmer ➝ Many plots
* One plot ➝ Many yield records
* One plot ➝ Many irrigation logs

---


## 🚀 Key Features

* Relational database design with foreign keys
* Real-world agricultural analytics
* Use of JOINs, GROUP BY, HAVING, and subqueries
* Performance-focused SQL queries

---

## 🛠️ Tools Used

* MySQL / SQL
* Database concepts (DDL, DML, Joins, Aggregations)

---

## 📈 Insights Generated

* Best performing crops and plots
* Water consumption patterns
* Weather impact on yield
* Efficient vs inefficient farming practices

---

## 📌 Conclusion

This project demonstrates how SQL can be used to **analyze agricultural productivity and optimize resource usage**, making it valuable for data analytics and real-world farming insights.

