# DSA210 Individual Project: "Analysis of the Impact of COVID-19 on Online Shopping Behavior and Product Category Demand"

**DSA210 Individual Project - Sabancı University, Fall 2025-2026**

*Prepared by : Ali Kaan Koç*

*Student ID: 33832*

---

## 📌 Contents
1. [Overview](#overview-)
2. [Research Question & Sub-Questions](#research-question--sub-questions-)
3. [Hypothesis](#hypothesis-)
4. [Project Goal](#project-goal-)
5. [Data Collection](#data-collection-)
6. [Data Sources](#data-sources-)
7. [Expected Outcomes](#expected-outcomes-)

---

## Overview 📝
This project investigates the impact of the COVID-19 pandemic on global online shopping demand, focusing on fluctuations in purchasing behavior across various product categories. By analyzing daily purchase quantities and their sales values, the study aims to reveal how consumer behavior shifted during the pandemic period. The comparison between pre-pandemic, pandemic, and post-pandemic phases will help determine whether the alterations in online shopping demand were temporary responses to lockdown restrictions or a longer-term shift in online consumer habits.

---

## Research Question & Sub-Questions 🔍

**Research Question:**

How did global online shopping demand and category-level purchasing behavior change across the pre-pandemic, pandemic, and post-pandemic periods of COVID-19?


**Sub-Questions**
- Did online shopping demand rise significantly during the pandemic compared to the pre-pandemic period?
- Which product categories experienced the strongest fluctuations in daily demand during lockdown restrictions?
- Which countries showed the strongest rebound in online shopping demand after the pandemic period, and how does this compare to their pre-pandemic levels?
- Is the presence of lockdown restrictions associated with noticeable changes in daily online shopping demand?
- Did online demand remain permanently above pre-pandemic levels after restrictions were lifted?
- Can patterns in daily demand help distinguish between essential and non-essential product categories?

---

## Hypothesis ✅

**Null Hypothesis (H₀)**
There is no significant difference in daily online shopping demand between the pre-pandemic and pandemic periods.

**Alternative Hypothesis (H₁)**  
Daily online shopping demand increased significantly during the pandemic compared to the pre-pandemic period.

A statistical significance threshold of α = 0.05 will be used when evaluating the p-value for hypothesis testing.

---

## Project Goal 🎯
The aim of this project is to examine the impact of the pandemic on online shopping demand across multiple product categories and countries. The project compares the periods before,during, and after the pandemic to measure changes in consumer demand over time and to determine which product categories have experienced the most significant shifts. It also examines the influence of lockdown restrictions on demand fluctuations and evaluates whether online shopping behavior remained elevated after restrictions ended. The results will be supported with visual analysis, statistical testing, and machine learning models to give a clearer picture of how digital shopping habits were altered during this period.

---

## Data Collection 📥

For the project, the data were collected from numerous publicly available sources to build a thorough and reliable dataset. The steps of data collection were as follows:

1. **Searching for Relevant Data:**

Various open data platforms were reviewed to find datasets containing online sales transactions and pandemic-related government policy indicators. Keywords such as "online sales", "COVID-19 lockdown data" were used during search.

2. **Selecting Appropriate Datasets:**

Datasets that included daily purchase activity, order dates within the target analysis period, and product category and country information were prioritized. In addition, a global COVID-19 policy tracker was selected to identify lockdown dates/periods.

3. **Downloading and Organizing Data:**
   
The datasets were downloaded in CSV format from Kaggle. To keep data organized, all files were stored in a structured directory, allowing easier access during the preprocessing and merging phases.

---
## Data Sources 📊
### **1️⃣ Global Online Sales Dataset (2019)**
- **Content:** Daily online order records with product category and geographic information.
- **Usage in Project:** Provides insight into the immediate market conditions leading into the pandemic period.
- **Data:** `online_sales_dataset_for_2019.csv` [https://github.com/AliKaanKoc2/DSA210-COVID-Online-Shopping-Analysis/blob/main/online_sales_dataset_for_2019.csv]
- **Source:** [https://www.kaggle.com/datasets/jacksondivakarr/online-shopping-dataset]
  
### **2️⃣ Global Online Sales Dataset (2020–2025)**
- **Content:** Daily purchase activity including pandemic and transition to post-pandemic phases.
- **Usage in Project:** Enables the analysis of pandemic-driven behavioral shifts and long-term recovery.
- **Data:** `online_sales_dataset_for_2020-2025.csv` [https://github.com/AliKaanKoc2/DSA210-COVID-Online-Shopping-Analysis/blob/main/online_sales_dataset_for_2020-2025.csv]
- **Source:** [https://www.kaggle.com/datasets/yusufdelikkaya/online-sales-dataset]

### **3️⃣ COVID-19 Lockdown Policy Dataset**
- **Content:** Daily national lockdown policy indicators (stay-at-home requirements).
- **Key Variable:** `is_lockdown` (categorical scale measuring restriction severity)
- **Usage in Project:** Allows investigation of how lockdown restrictions impacted online demand.
- **Data:** `covid_policy-lockdown_tracker.csv` [https://github.com/AliKaanKoc2/DSA210-COVID-Online-Shopping-Analysis/blob/main/covid_policy-lockdown_tracker.csv]
- **Source:** [https://github.com/OxCGRT/covid-policy-tracker/blob/master/data/OxCGRT_nat_latest.csv]

**Data Fields Planned for Use (Online Shopping Dataset)**
- `OrderDate` → to segment pre-pandemic, pandemic, and post-pandemic phases
- `Category` → to measure category-specific demand shifts
- `Quantity` → to calculate daily demand levels
- `Country` → to compare recovery patterns between regions

**Data Field Planned for Use (COVID-19 Dataset)**
- `C6_Stay_at_home_requirements` → converted to a binary `is_lockdown` indicator

---
## Expected Outcomes 📈
- It is expected that online shopping demand will show a noticeable increase during the pandemic compared to the pre-pandemic period, especially in categories related to essential needs such as groceries and household products. Countries that faced longer or stricter lockdowns are anticipated to display sharper demand spikes and a slower return to normal levels.

- The project also expects that demand will remain above pre-pandemic levels in the post-pandemic period, indicating a long-term shift toward digital purchasing behavior. Machine learning models are expected to identify patterns in daily demand that help distinguish between essential and non-essential product categories based on consumer response during the pandemic.
