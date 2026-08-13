images/Screenshot 2026-08-13 164909.png


# Logistics & Transportation – Fleet Performance & Delivery Efficiency

## 📌 About the Project

This project analyzes the performance of a logistics company's fleet with a focus on **on-time deliveries, fuel efficiency, route performance, and transportation cost efficiency**.

The objective is to provide an interactive Power BI dashboard that helps identify underperforming routes and vehicles and supports better fleet utilization and route optimization.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Analyze on-time and late delivery performance.
* Measure fuel efficiency of the fleet.
* Compare delivery performance across different routes.
* Analyze vehicle utilization and performance.
* Calculate transportation cost per kilometer.
* Identify routes and vehicles that require operational improvement.

---



## 🧹 Data Cleaning & Preprocessing

The data was initially reviewed and cleaned in **Microsoft Excel** before importing it into Power BI.

The following preprocessing activities were performed:

* Checked for missing values.
* Verified and corrected Trip IDs.
* Corrected inconsistent distance values.
* Converted distance and other numerical fields into appropriate data types.
* Checked delivery status values for consistency.
* Verified delivery dates.
* Checked the Vehicle Master table for missing or inconsistent records.

---

## 🔗 Data Modeling

The cleaned data was imported into **Power BI**.

A relationship was established between:

**Vehicle Master → Table1**

using:

`Vehicle ID`

The Vehicle Master table has a **one-to-many relationship** with the Trip Data table because one vehicle can be associated with multiple trips.

A Route field was also created by combining Origin and Destination:

`Origin → Destination`

---

## 🧮 DAX Measures

### Fuel Efficiency
### Total Trips
### On-Time Trips
### On-Time Delivery %
### Late Trips
### Total Distance

## 📈 Dashboard & Visualizations

The Power BI dashboard contains the following key visualizations:

### KPI Cards

* Total Trips
* On-Time Delivery %
* Fuel Efficiency
* Cost per Kilometer

### Charts



## 🔍 Key Insights

* Several routes achieved **100% on-time delivery**, indicating strong route performance.
* Some routes recorded **0% on-time deliveries**, highlighting areas that require operational attention.
* Route-level analysis helps identify delivery bottlenecks and opportunities for route optimization.
* Comparing fuel efficiency across vehicles can help identify vehicles that are more economical for longer-distance trips.

---

## 💡 Business Recommendations

Based on the analysis, the logistics company can:

* Investigate routes with consistently high late-delivery rates.
* Prioritize fuel-efficient vehicles for longer-distance trips.
* Monitor vehicles with relatively high fuel consumption.
* Optimize routes with poor delivery performance.
* Use dashboard insights to improve fleet utilization and reduce transportation costs.

---

## 🛠️ Tools Used

* **Microsoft Excel** – Data cleaning and preprocessing
* **Power BI Desktop** – Data modeling, DAX calculations, and dashboard development
* **GitHub** – Project version control and documentation



