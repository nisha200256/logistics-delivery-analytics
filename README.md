# Logistics Delivery Analytics

## From Messy Shipment Data to Actionable Insights

An end-to-end data analytics project focused on cleaning shipment data, analyzing delivery performance, and developing an interactive Power BI dashboard to generate actionable logistics insights.

## Project Overview

This project analyzes shipment records across carriers, warehouses, destination zones, delivery modes, and routes.

The project workflow includes:

* Data quality assessment
* Data cleaning and standardization
* Exploratory data analysis
* Feature engineering
* Power BI dashboard development
* Business insights and recommendations

## Dataset

* **Raw shipment records:** 1,630
* **Cleaned shipment records:** 1,562
* **Carriers analyzed:** 6
* **Destination zones:** 4
* **Original columns:** 20
* **Final columns:** 22

## Data Cleaning

The raw dataset contained several data-quality issues, including:

* Duplicate shipment records
* Inconsistent text formatting
* Mixed date formats
* Missing and placeholder values
* Inconsistent carrier, city, zone, and status values

The cleaning process included:

* Removing duplicate shipment records
* Standardizing categorical values
* Converting mixed date formats
* Handling placeholder values such as `N/A` and `-`
* Creating `Transit_Days`
* Creating `Delivery_Delay_Days`

## Power BI Dashboard

The interactive Power BI dashboard contains three main analytical areas:

### 1. Executive Overview

* Total shipments
* Delivery status
* Delivered rate
* Delayed rate
* Average distance
* Key logistics KPIs

### 2. Carrier Performance

* Delay rate by carrier
* Carrier comparison
* Vehicle-type analysis

### 3. Zone & Route Analysis

* Delivery delays by destination zone
* Warehouse analysis
* Distance and transit-time patterns

## Key Insights

* Delivered shipments represented **41%** of the analyzed records.
* Delayed shipments represented **13.8%**.
* Cancelled shipments represented **15.8%**.
* Carrier delay rates ranged from **11.7% to 16.3%**.
* XpressBees recorded the lowest delay rate in the project analysis at **11.7%**.
* South handled the highest shipment volume and had the lowest average delay among the analyzed zones.
* Transit time and delivery delay showed a reported correlation of **0.60**.

## Business Recommendations

* Review carrier allocation for East and North zone shipments.
* Investigate long-transit routes and hand-off points.
* Analyze the causes of shipment cancellations.
* Improve source-data quality using standardized carrier, city, and zone values.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Power BI
* Power Query
* DAX
* Exploratory Data Analysis
* Data Cleaning
* Feature Engineering
* KPI Analysis
* Business Intelligence

## Project Files

| File                                  | Description                                |
| ------------------------------------- | ------------------------------------------ |
| `Logistics_data.ipynb`                | Python data cleaning and analysis notebook |
| `LOGISTICS_DASHBOARD.pbix`            | Interactive Power BI dashboard             |
| `Logistics_Project_Presentation.pptx` | Project presentation                       |

## Skills Demonstrated

* Data Cleaning & Standardization
* Exploratory Data Analysis
* Data Visualization
* Power BI Dashboard Development
* Power Query
* DAX
* KPI Development
* Business Insight Generation
* Data-Driven Recommendations

## Project Workflow

**Raw Shipment Data → Data Cleaning → Feature Engineering → EDA → Power BI Dashboard → Business Insights → Recommendations**

---

**Created by Nisha K G**
Data Analyst | Python | SQL | Power BI
