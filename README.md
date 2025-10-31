# DSA210 Individual Project: Analysis of the Impact of COVID-19 on Online Shopping Behavior and Product Category Demand

**DSA210 Individual Project - Fall 2025-2026 - Sabancı University**

*Prepared by : Ali Kaan Koç*

---

## Contents
1. [Overview](#overview)
2. [Motivation](#motivation)
3. [Research Question & Sub-Questions](#research-question--sub-questions)
4. [Hypothesis](#hypothesis)
5. [Project Goal](#project-goal)
6. [Data Collection](#data-collection)
7. [Data Sources](#data-sources)
8. [Expected Outcomes](#expected-outcomes)
   
---

## Overview 
This project examines the impact of the COVID-19 pandemic on global online shopping practices, mainly focusing on fluctuations in purchasing behavior across various product categories. By analyzing daily purchase counts and products prices, i expect to understand how consumer behavior shifted during the pandemic period. The comparison between 3 periods will show if the lockdowns were one of the leading reason why people started shopping online on a greater scale, and if the shift and the scale remained the same after the lockdowns were lifted.

---
## Motivation 

As a data science student, I am interested in how major global events influence online shopping habits and everyday decision-making. The COVID-19 pandemic created one of the most significant shifts in consumer habits,which increased online shopping dependence.Like many households, mine also began relying heavily on digital platforms for both essential and non-essential purchases during lockdown periods. Studying this shift will help me explore how consumer preferences change under disruptive conditions using data-driven analysis.

---
## Research Question & Sub-Questions 

**Research Question:**

- How did global online shopping demand and category-level purchasing behavior change across the pre-pandemic, pandemic, and post-pandemic periods of COVID-19?


**Sub-Questions**
- Did online shopping demand rise significantly during the pandemic compared to the pre-pandemic period?
- Which product categories experienced the strongest changes in daily demand during lockdown restrictions?
- Do lockdown restrictions lead to noticeable changes in daily online shopping demand?
- Did online demand remain permanently above pre-pandemic levels after restrictions were lifted?

---

## Hypothesis 

**Null Hypothesis (H₀)**
There is no significant difference in daily online shopping demand between the pre-pandemic and pandemic periods.

**Alternative Hypothesis (H₁)**  
Daily online shopping demand increased significantly during the pandemic compared to the pre-pandemic period.

A statistical significance threshold of α = 0.05 will be used when evaluating the p-value for hypothesis testing.

---

## Project Goal 
The project investigates how the COVID-19 pandemic changed the way people buy products on online platforms globally, especially which types of categories products people bought more and how this varied from country to country.
I also look at how lockdown restrictions affected the scale of online purchases and if people kept shopping online more often even though the restriction were lifted.

---

## Data Collection 

For this project, I collected the data from numerous publicly available sources to create a large and reliable dataset. Below, I explain the steps of my data collection process in detail:

**1 - Looking for Relevant Data:**
I searched multiple open data platforms for datasets on online sales and pandemic-related policies, using keywords like “online sales” and “COVID-19 lockdown data” to guide the process.

**2 - Selecting Usefull Datasets:**
I focused on datasets that provided daily purchase activity, product category and country details during the analysis period. In order to connect shopping patterns with COVID-19 period, I also included a global pandemic dataset that shows the date range of lockdowns.

**3 - Downloading and Storing Data:**
The datasets were downloaded in CSV format from Kaggle and stored in my project repository. All of the necessary files will be cleaned and merged in the future.

---
## Data Sources 
### **1️ - Global Online Sales Dataset (2019)**
- **Content:** Product category, product purchase date, value of the product and country that it was purchased from.
- **Usage in Project:** It will provide a solid foundation to the pre-pandemic period.
- **Data:** `online_sales_dataset_for_2019.csv` [https://github.com/AliKaanKoc2/DSA210-COVID-Online-Shopping-Analysis/blob/main/online_sales_dataset_for_2019.csv]
- **Source:** [https://www.kaggle.com/datasets/jacksondivakarr/online-shopping-dataset]
  
### **2️ - Global Online Sales Dataset (2020–2025)**
- **Content:** Product category, item purchase date, value of the product and country that it was purchased from, information about review.
- **Usage in Project:** It will be a baseline for pandemic and post-pandemic period.
- **Data:** `online_sales_dataset_for_2020-2025.csv` [https://github.com/AliKaanKoc2/DSA210-COVID-Online-Shopping-Analysis/blob/main/online_sales_dataset_for_2020-2025.csv]
- **Source:** [https://www.kaggle.com/datasets/yusufdelikkaya/online-sales-dataset]

### **3️ - COVID-19 Lockdown Policy Dataset**
- **Content:** Contains every countries case count, the strictness of the lockdown, the specific dates of the lockdown for all countries.
- **Key Variable:** A binary (0-1) variable `is_lockdown` will be created and included in the merged csv files.
- **Usage in Project:** The created variable will show the dates when the country had a lockdown.
- **Data:** `covid_policy-lockdown_tracker.csv` [https://github.com/AliKaanKoc2/DSA210-COVID-Online-Shopping-Analysis/blob/main/covid_policy-lockdown_tracker.csv]
- **Source:** [https://github.com/OxCGRT/covid-policy-tracker/blob/master/data/OxCGRT_nat_latest.csv]

---
## Expected Outcomes 
- I expect that online shopping trends will increase immensely compared to the pre-pandemic period, especially in categories linked to essential needs such as groceries and household products. Additionally, the alteration in human shopping habits will keep them making online purchases more compared to pre-Covid period.

