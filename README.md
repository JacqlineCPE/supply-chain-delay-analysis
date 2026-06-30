# Supply Chain Delay Root Cause Analysis

## Project Overview

Late deliveries can increase operational costs, reduce customer satisfaction, and impact business performance. This project analyzes **180,519 supply chain orders** from the DataCo Smart Supply Chain dataset to identify the major drivers of delivery delays across shipping methods, markets, regions, departments, and time.

The objective is to uncover the root causes of delayed deliveries and provide data-driven recommendations that can help logistics and operations teams improve delivery performance.

---

## Business Questions

This analysis answers the following questions:

- What percentage of orders are delivered late?
- Which shipping mode contributes the most to late deliveries?
- Which markets and regions experience the highest delivery delays?
- Which departments generate the most delayed orders?
- How have late deliveries changed over time?
- Which customer segments experience the greatest delivery delays?

---

## Dataset

- **Source:** DataCo Smart Supply Chain Dataset (Kaggle)
- **Records:** 180,519 orders
- **Period Covered:** 2015–2018

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib

---

## Data Preparation

The dataset was prepared through the following steps:

- Removed duplicate records
- Checked for missing values
- Removed personally identifiable information (PII)
- Dropped columns with excessive missing values and low analytical value
- Converted date columns to datetime format
- Created a new **Delay Gap** feature (Actual Shipping Days − Scheduled Shipping Days)

---

## Analysis Performed

The analysis explored delivery performance across multiple business dimensions, including:

- Overall delivery performance
- Shipping mode analysis
- Market analysis
- Regional analysis
- Department performance
- Product-level delays
- Customer segment analysis
- Order status analysis
- Monthly and yearly delivery trends

---

## Key Findings

- **55%** of all orders were delivered late.
- **Standard Class** accounted for **41%** of all late deliveries.
- The **LATAM** market contributed the largest share of delayed orders (**28.33%**).
- **Central America** recorded the highest proportion of delayed deliveries among regions.
- The **Fan Shop** department generated the highest number of late deliveries.
- Delivery delays were most prevalent during **2015–2016**, while **January** consistently recorded the highest monthly delay volume.

---

## Business Recommendations

- Investigate operational bottlenecks affecting Standard Class shipping.
- Prioritize logistics improvements within the LATAM market.
- Review inventory and fulfillment processes for the Fan Shop department.
- Implement delivery performance monitoring dashboards to track delay trends.
- Monitor seasonal demand and allocate resources proactively during peak periods.

---

## Dataset Link:
https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis?select=DataCoSupplyChainDataset.csv
