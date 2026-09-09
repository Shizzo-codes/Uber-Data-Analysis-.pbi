<img width="2575" height="1482" alt="overview-analysis" src="https://github.com/user-attachments/assets/9ff04d25-eae9-4c82-8d84-a9c90056d624" /><img width="2575" height="1482" alt="overview-analysis" src="https://github.com/user-attachments/assets/65117699-649a-4415-8cba-91ab1391b82b" />[README.md](https://github.com/user-attachments/files/32011102/README.md)

# 🚗 Uber Trip Analysis — Power BI Dashboard

A multi-page Power BI dashboard analyzing Uber trip data to uncover booking trends, revenue patterns, and trip efficiency — built to help stakeholders make data-driven decisions.

---

## 📌 Project Overview

This project analyzes Uber trip data using Power BI to answer key business questions around bookings, revenue, trip efficiency, and demand patterns. It was built as a personal project to practice translating raw operational data into an interactive, decision-ready dashboard.

**Business Objective:** Analyse Uber trip data to gain insights into booking trends, revenue, and trip efficiency — helping stakeholders make data-driven decisions.

---

## 🎯 Key KPIs

- **Total Bookings** — How many trips were booked over a given period?
- **Total Booking Value** — Total revenue generated from all bookings
- **Average Booking Value** — Average revenue per booking
- **Total Trip Distance** — Total distance covered across all trips
- **Average Trip Distance** — Average distance traveled per trip
- **Average Trip Time** — Average duration of trips

**Sample results (June 2024 dataset):** 103.7K total bookings, $1.6M total booking value, $15.0 average booking amount, 348.9K miles total trip distance, 16 min average trip time.

---

## 📊 Dashboards

### 1. Overview Analysis
- Dynamic **Measure Selector** (disconnected table) to toggle between Total Bookings, Total Booking Value, and Total Trip Distance
- Breakdown **by Payment Type** (Card, Cash, Wallet, etc.) and **Trip Type** (Day/Night)
- Dynamic chart titles that update based on selected measure
- Slicers for Date, City, and other filters
- Tooltips showing Average Booking Value / Trip Distance
- **Vehicle Type Analysis** — matrix/table visual comparing KPIs across vehicle types, with conditional formatting to flag high/low performers
- **Total Bookings by Day** — trend detection, peak/off-peak identification
- **Location Analysis:**
  - Most frequent pickup point
  - Most frequent drop-off point (via activated inactive relationship between pickup and drop-off tables)
  - Farthest trip by distance
  - Top 5 locations by booking volume
  - Most preferred vehicle type per pickup location

**Extras:** "Data Details" bookmark explaining key metrics, a Clear Filters/Reset Slicers button, and a raw data export (CSV/Excel) button.

### 2. Time Analysis
- Global dynamic measure selector filtering all visuals on this page
- **By Pickup Time** (10-minute intervals) — Area chart showing demand across the day
- **By Day Name** — Line chart comparing weekday vs. weekend demand
- **By Hour & Day** — Heatmap (matrix) highlighting peak booking hours across the week

### 3. Details Tab
- Grid table with key trip-level fields
- Drill-through functionality from other dashboard visuals into detailed records
- "View Full Data" bookmark to toggle between filtered drill-through data and the complete dataset

---

## 🛠️ Tools & Techniques Used

- **Power BI** — data modeling, DAX measures, interactive visuals
- Disconnected tables for dynamic measure selection
- Bookmarks & buttons for enhanced UX (filter reset, data details, full data view)
- Drill-through pages for granular exploration
- Conditional formatting for quick visual insights
- Relationship management (activating inactive relationships for pickup/drop-off analysis)

---

## 📷 Screenshots

**Overview Analysis**
<img width="2575" height="1482" alt="overview-analysis" src="https://github.com/user-attachments/assets/5e1af75b-e6bf-4ff0-a777-0951f069a132" />


**Time Analysis**
<img width="2575" height="1482" alt="time-analysis" src="https://github.com/user-attachments/assets/489aaece-feca-44f0-a091-cb32811b7b01" />


**Details Tab**
<img width="2575" height="1482" alt="details-tab" src="https://github.com/user-attachments/assets/ff66b018-dd37-41c9-9a14-9217a9dfbd41" />


---

## 🚀 Outcomes

- Identified trends in ride bookings and revenue generation
- Analyzed trip efficiency in terms of distance and duration
- Compared booking values and trip patterns across time periods
- Surfaced insights to support pricing strategy and customer satisfaction

---

## 📬 Contact

Built by **Sina Kolawole** — Data Analyst | Founder, [The Spreadsheet Noob](#)
Feel free to connect or reach out with feedback!
