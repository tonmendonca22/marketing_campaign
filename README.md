# 📊 Marketing Campaign Analysis

This project analyzes a comprehensive marketing campaign dataset to uncover insights into customer behavior, spending patterns, and campaign effectiveness. The goal is to generate actionable recommendations to help businesses optimize their marketing strategies and customer targeting.

## 📁 Dataset Overview

The dataset (`marketing_campaign_data.csv`) includes detailed information for 2,240 customers, covering:

- **Demographics**:  
  `ID`, `Year_of_Birth`, `Education_Level`, `Marital_Status`, `Annual_Salary`, `Children_at_Home`, `Teens_at_Home`, `Country`

- **Behavioral Metrics**:  
  `Registration_Date`, `Days_Since_Last_Purchase`, `Electronics_Spending`, `Toy_Spending`, `Furniture_Spending`, `Utilities_Spending`, `Food_Spending`, `Clothing_Spending`,  
  `Number_of_Discount_Purchases`, `Number_of_Web_Purchases`, `Number_of_Catalog_Purchases`, `Number_of_Store_Purchases`, `Number_of_Website_Visits_per_Month`

- **Campaign Responses**:  
  `Campaign_1_Purchase`, `Campaign_2_Purchase`, `Campaign_3_Purchase`, `Campaign_4_Purchase`, `Campaign_5_Purchase`, `Purchased` (any campaign)

---

## 📈 Analysis Summary

The data analysis was performed using **React** and **Recharts**, resulting in an interactive report that presents the following key insights:

- **🇵🇹 Portugal** customers had the **highest average spending**, making them ideal targets for premium campaigns.
- **🎓 Doctorate holders** had the **highest purchase rate**, despite lower spending, suggesting strong conversion potential.
- **👵 The 61+ age group** demonstrated the **highest average spending**, likely due to disposable income.
- **📢 Campaign 2** showed the **best performance (~5.6% success rate)**, deserving further analysis.
- **🇨🇱 Elementary-educated customers in Chile** had high purchase rates, revealing an untapped budget-conscious segment.

---

## 📂 Repository Structure

