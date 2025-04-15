# 🚕 Uber Trip Data Analysis Dashboard

This project provides a comprehensive **Power BI dashboard** that analyzes Uber trip data to deliver business insights related to ride trends, revenue patterns, efficiency metrics, and operational optimization.

---

## 📌 Business Objective

To help Uber and its stakeholders make **data-driven decisions** by analyzing trip-related data such as:
- Booking trends
- Revenue generation
- Trip distances and durations
- Location-based ride demand
- Vehicle type preferences

---

## 📊 Dashboards Overview

### 📁 **Dashboard 1: Overview Analysis**
- Analyze total bookings, revenue, and trip efficiency.
- KPIs:
  - Total Bookings
  - Total Booking Value
  - Average Booking Value
  - Total Trip Distance
  - Average Trip Distance
  - Average Trip Time
- Filters:
  - Payment Type
  - Trip Type (Day/Night)
  - City
  - Date
- Visual Elements:
  - Dynamic Title
  - Measure Selector
  - Tooltips
  - Vehicle Type Grid Analysis
  - Bookings by Day

### 📍 **Dashboard 2: Time Analysis**
- Visualizes time-based trip patterns to understand peak demand periods.
- Charts:
  - Pickup Time (10-Minute Intervals) – Area Chart
  - Day Name – Line Chart
  - Hour × Day – Heatmap (Matrix)
- Dynamic measure filters to toggle between:
  - Total Bookings
  - Booking Value
  - Trip Distance

### 📋 **Dashboard 3: Details Tab**
- Drill-through tab to view individual trip records.
- Features:
  - Grid table with key fields
  - Drill-through from other dashboards
  - "View Full Data" bookmark toggle

---

## 📂 Data Model

### **Trip Details Table**
| Column Name        | Description |
|--------------------|-------------|
| Trip ID            | Unique trip identifier |
| Pickup/Drop-off Time | Date and time of pickup and drop-off |
| Passenger Count    | Number of passengers per trip |
| Trip Distance      | Distance covered (miles) |
| PULocationID/DOLocationID | Pickup/Drop-off location codes |
| Payment Type       | Card, Cash, Wallet, etc. |
| Fare Amount        | Base fare for trip |
| Surge Fee          | Additional charge for high-demand |
| Vehicle            | UberX, UberXL, Uber Black, etc. |

### **Location Table**
| Column Name | Description |
|-------------|-------------|
| LocationID  | Unique area identifier |
| Location    | Area or neighborhood name |

---

## 🚀 Features & Enhancements

- 📌 **Measure Selector** – dynamically change KPIs
- 🧭 **Dynamic Titles** – visual titles update with KPI selection
- 🔎 **Slicers** – for interactive filtering by time and geography
- 📈 **Vehicle Type Grid View** – KPI breakdown by vehicle type
- 📍 **Location Analysis** – identify frequent pickup/drop-off points
- 🌐 **Drill-through & Bookmarks** – in-depth record inspection and toggling views
- 📤 **Download Raw Data Button** – export raw data to CSV/Excel
- 🔄 **Clear Filters Button** – resets all filters for user convenience

---

## 🛠 Tools & Technologies

- **Power BI** (main visualization tool)
- **DAX** (for calculated measures and dynamic filtering)
- **Power Query** (for data transformation)
- **Power Automate** *(optional: for export functionality)*

---

## 📈 Business Outcomes

- Identify booking trends, customer behavior, and revenue patterns
- Analyze trip efficiency and distance trends
- Optimize operations and pricing models
- Improve driver availability and satisfaction by location and time

---

## 📁 Project Structure

