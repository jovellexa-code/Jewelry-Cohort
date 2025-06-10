# 💎 Decoding Luxury Buying Behavior: Cohort Retention Analysis of a Jewelry E-Commerce (2018–2021)
Final Project | Customer Analytics & Retention Strategy

## 📌 Overview
This project investigates customer retention behavior in a jewelry e-commerce business using Cohort Analysis. By segmenting users based on their first purchase month, we identify which customer groups show long-term loyalty and which drop off early — revealing insights for targeted engagement strategies.
The dataset spans from 2018 to 2021, a period marked by major shifts such as the COVID-19 pandemic, which significantly affected luxury purchase patterns.

## 🧠 Business Understanding
Jewelry purchases often reflect both emotional and investment value. However, the company faces challenges retaining high-value customers. Without knowing which cohorts perform best, marketing efforts risk being ineffective or misallocated.

### Main Objective: 🎯 Improve customer retention by 10% in 6 months by understanding and acting upon insights from top-performing cohorts.

## 📊 Methodology
The project follows this structured approach:
1. Data Cleaning & Preprocessing
    * Convert and format InvoiceDate, CustomerID, etc.
    * Remove nulls, duplicates, and irrelevant transactions.
2. Cohort Analysis Construction
    * Define cohorts by customer acquisition month.
    * Calculate Cohort (months since acquisition).
    * Create a cohort-based retention.
3. Retention Heatmap Visualization
    * Visualize how long customers stay active after first purchase.
    * Compare retention patterns across cohorts.
4. Retention Metrics Extraction
    * Calculate monthly retention rate.
    * Identify the best and worst-performing cohorts.

## 📈 Key Findings
* Retention sharply drops after month 1 for most cohorts.
* A few specific cohorts (e.g., Q4/2019 and Q2/2020) had above-average long-term engagement.
* Seasonality (e.g., festive sales) influences cohort size and retention.
* COVID-era cohorts showed initial spikes but lower long-term retention.

## 📂 Dataset
Data was obtained from a jewelry e-commerce platform and includes:
Feature	Description
InvoiceNo	Transaction code
CustomerID	Unique buyer identifier
InvoiceDate	Purchase date
Quantity	Items bought
Price	Item price

## 🛠️ Tools & Libraries
* Python 3.9+
* pandas, numpy for data manipulation
* matplotlib, seaborn for visualization
* datetime for time-based indexing


## 📌 Business Impact
Insights from cohort retention will support:
* More targeted re-engagement campaigns
* Efficient allocation of marketing budget
* Seasonal cohort-specific strategies
* Benchmarking retention KPIs by cohort

## 👤 Author
Kaila Amira Azzahra
Meriani Alexandra
Nadame Kristina
