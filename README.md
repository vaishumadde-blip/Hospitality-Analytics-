# 🏨 Hospitality Analytics

An end-to-end **Hospitality Analytics project** focused on analyzing hotel bookings, revenue, occupancy, cancellations, customer behavior, room performance, and key business KPIs.

The project was developed using **Excel, SQL, Power BI, and Tableau** to transform raw booking data into meaningful business insights and interactive dashboards.

---

## 📌 Project Overview

The hospitality industry generates large volumes of booking and revenue data. This project analyzes hotel booking data to understand:

* Hotel and room performance
* Revenue generation
* Occupancy trends
* Booking and cancellation patterns
* Customer behavior
* Booking platform performance
* Average Daily Rate (ADR)
* Revenue per Available Room (RevPAR)
* Week-over-Week (WoW) performance

The objective is to help stakeholders understand business performance and make data-driven decisions.

---

## 🎯 Business Objectives

The main objectives of this project are:

1. Analyze hotel booking performance.
2. Monitor revenue and occupancy trends.
3. Analyze booking and cancellation patterns.
4. Compare hotel and room performance.
5. Understand customer and booking behavior.
6. Analyze booking channels/platforms.
7. Calculate important hospitality KPIs.
8. Build interactive dashboards for business reporting.

---

## 🗂️ Dataset

The dataset contains hotel booking and operational information.

### Main tables

| Table                      | Description                                      |
| -------------------------- | ------------------------------------------------ |
| `dim_date`                 | Date, week number and day type information       |
| `dim_hotels`               | Hotel/property details                           |
| `dim_rooms`                | Room category information                        |
| `fact_bookings`            | Individual booking-level information             |
| `fact_aggregated_bookings` | Aggregated booking and room capacity information |

### Key columns in `fact_bookings`

* Booking ID
* Property ID
* Booking Date
* Check-in Date
* Checkout Date
* Number of Guests
* Room Category
* Booking Platform
* Ratings
* Booking Status
* Revenue Generated
* Revenue Realized

---

## 🧹 Data Cleaning

The raw dataset was reviewed and cleaned before analysis.

The cleaning process included:

* Checking missing values
* Checking duplicate records
* Validating data types
* Standardizing columns
* Creating required calculated fields
* Preparing data for analysis and visualization

The cleaned dataset is available inside the `Dataset/cleaned` folder.

---

# 📊 Key KPIs

The project analyzes several important hospitality KPIs.

### Occupancy %

Measures the percentage of available room capacity that was successfully occupied.

```text
Occupancy % = Successful Bookings / Capacity × 100
```

### ADR

Average Daily Rate represents the average revenue earned per room sold.

```text
ADR = Revenue Realized / Rooms Sold
```

### RevPAR

Revenue Per Available Room measures revenue performance across available room capacity.

```text
RevPAR = Revenue Realized / Available Room Capacity
```

### Cancellation %

Measures the percentage of bookings that were cancelled.

```text
Cancellation % = Cancelled Bookings / Total Bookings × 100
```

### Realization %

Measures the percentage of generated revenue that was actually realized.

```text
Realization % = Revenue Realized / Revenue Generated × 100
```

### WoW Analysis

Week-over-Week analysis was used to compare:

* Revenue
* Occupancy
* ADR
* RevPAR

with the previous week.

---

# 🛠️ Tools & Technologies

### Excel

* Data Cleaning
* Pivot Tables
* Pivot Charts
* KPI Analysis
* Interactive Dashboard
* Slicers

### SQL / MySQL

* SELECT
* WHERE
* GROUP BY
* JOIN
* CASE
* Aggregate Functions
* Subqueries
* CTEs
* Window Functions
* LAG
* KPI calculations

### Power BI

* Data Modeling
* Power Query
* DAX
* KPI Cards
* Interactive Charts
* Slicers
* Dashboard Development

### Tableau

* Interactive Dashboards
* KPI Cards
* Filters
* Charts
* Hotel Performance Analysis
* Revenue Analysis

---

# 📈 Dashboard Pages

## 1. Executive Overview

Provides an overall view of hotel business performance.

Key metrics include:

* Revenue
* Successful Bookings
* Occupancy %
* ADR
* RevPAR
* Total Capacity

---

## 2. Booking Analysis

Analyzes:

* Booking volume
* Booking platforms
* Cancellation trends
* Booking status
* Hotel performance

---

## 3. Revenue & Room Analysis

Focuses on:

* Revenue trends
* ADR
* RevPAR
* Room category performance
* Hotel revenue performance

---

## 4. Customer Analysis

Analyzes:

* Customer type
* Customer location
* Stay duration
* Booking behavior
* Customer trends

---

# 🔍 Key Business Insights

The analysis helps identify:

* Revenue and occupancy trends over time
* Differences in performance between properties
* Booking platform contribution
* Cancellation patterns
* Room category performance
* Customer booking behavior
* Weekly changes in revenue and hospitality KPIs

These insights can help hotel management monitor performance and identify areas requiring attention.

---

# 📁 Project Structure

```text
Hospitality-Analytics/
│
├── Dataset/
│   ├── raw/
│   └── cleaned/
│
├── Excel/
│   └── Hospitality_Analytics_Final.xlsx
│
├── PowerBI/
│   └── Hospitality_Analytics_Final.pbix
│
├── Tableau/
│   └── Hospitality_Analytics_Final.twbx
│
├── SQL/
│   ├── database.sql
│   ├── dim_date.sql
│   ├── dim_hotels.sql
│   ├── dim_rooms.sql
│   ├── fact_aggregated_bookings.sql
│   ├── fact_bookings.sql
│   └── KPI_queries.sql
│
├── Presentation/
│   └── Hospitality_Analytics_Presentation.pptx
│
├── Screenshots/
│   ├── dashboard_excel.png
│   ├── dashboard_powerbi.png
│   └── dashboard_tableau.png
│
└── README.md
```

---

# 🚀 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
SQL Analysis
     ↓
Excel Analysis
     ↓
Power BI Dashboard
     ↓
Tableau Dashboard
     ↓
Business Insights
```

---

# 💡 Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Data Analysis
* Exploratory Data Analysis
* SQL
* Excel
* Power BI
* Tableau
* Data Visualization
* KPI Development
* Dashboard Development
* Business Analysis
* Business Intelligence

---

# 👩‍💻 Author

**Vaishnavi Madde**

BTech Computer Science & Engineering Graduate
Aspiring Data Analyst

### Skills

`Excel` `SQL` `Power BI` `Tableau` `Python` `Pandas` `Data Analysis`

---

## ⭐ Project

This project was created as part of a Data Analytics learning/project program and demonstrates an end-to-end approach to solving a real-world business analytics problem.
