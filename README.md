<img width="1983" height="793" alt="Panoramico GitHub" src="https://github.com/user-attachments/assets/c66f0fde-9a04-4177-9da3-dbc779c738bb" />

# Bike IShop Sales Analysis | Excel Dashboard

## 1. Project Description

This project presents an interactive dashboard developed in Microsoft Excel to analyze the purchasing behavior of customers from a bicycle retail company called **Bike IShop**.

### Project Objective

The goal of this analysis is to identify the demographic, economic, and social factors that influence customers' purchasing decisions. Based on these findings, business recommendations are provided to help improve marketing strategies, address the problems outlined below, and support data-driven decision-making.

## 2. Business Problem (Ask)

Bike IShop is a bicycle retail company operating in multiple regions (North America, Pacific, and Europe). Recently, the company has experienced a decline in bicycle sales and wants to better understand which customer characteristics have the greatest influence on purchasing decisions, in order to identify opportunities to improve its marketing strategy, better segment its customers, and increase sales.

The following business questions were defined:

- Which age group purchases the most bicycles?
- Does the customer's occupation influence the decision to purchase a bicycle?
- Does education level influence bicycle purchases?
- Are higher-income customers more likely to purchase a bicycle?
- How does commuting distance affect customers' purchasing decisions?

## 3. About the Dataset (Prepare)

The dataset contains information about customers who attempt to purchase a bicycle through the company's website, including data such as:

- Customer ID
- Marital Status
- Gender
- Annual Income
- Number of Children
- Education
- Occupation
- Home Owner
- Number of Cars
- Commute Distance
- Region
- Age
- Bicycle Purchase Decision

[Dataset]([https://tu-enlace.com](https://github.com/said16ed/bike-sales-analysis-excel/blob/main/excel-bike-sales-dataset.xlsx)) 

## 4. Data Cleaning (Process)

The following changes were made to the dataset:

**Marital Status**
- M → Married
- S → Single

**Gender**
- M → Male
- F → Female

**New column: Age Brackets**
- Adolescent (under 18 years old)
- Middle Age (18–60 years old)
- Old (over 60 years old)

After completing the data cleaning process, the dataset was organized and structured to facilitate analysis using Pivot Tables and Pivot Charts in Microsoft Excel.

<img width="1960" height="837" alt="imagen1" src="https://github.com/user-attachments/assets/8a13d294-4d77-431a-9060-34a8c264060f" />

## 5. Exploratory Data Analysis (Analyze)

### Which age group purchases the most bicycles?

Customers were grouped into different age categories to identify which segment purchases the most bicycles. This visualization highlights the age group that represents the company's primary target market.

<img width="1198" height="892" alt="imagen2" src="https://github.com/user-attachments/assets/3286b087-a3c9-460e-8b3f-415d57a0f1cb" />

The analysis shows that customers in the Middle Age (18–60 years old) category represent the largest group of bicycle buyers. In contrast, customers classified as Old (over 60 years old) have a significantly lower purchase rate, while no bicycle purchases were recorded for the Adolescent group.

**Key Insight:** The company's primary target market consists of customers between 18 and 60 years old, making this age group the most attractive segment for future marketing campaigns.

### Does the customer's occupation influence the decision to purchase a bicycle?

Customers working in Professional and Skilled Manual occupations account for the highest proportion of bicycle purchases. Among these groups, professionals represent the largest number of buyers. However, within Skilled Manual there is also a high share of customers who choose not to buy a bicycle, and across the remaining occupations the number of non-buyers is higher than the number of buyers.

<img width="1976" height="782" alt="imagen3" src="https://github.com/user-attachments/assets/97b02ced-7e66-4ab3-b50d-164d904ffe59" />

**Key Insight:** Customers employed in professional occupations appear to have a greater likelihood of purchasing bicycles, making them valuable target segments for future promotional campaigns.

### Does education level influence bicycle purchases?

Based on the charts, customers with a Bachelors degree show the highest number of buyers compared to non-buyers, suggesting this should be a key target audience. This could be related to the fact that many customers with a university education (Bachelors and Graduate Degree) also hold professional occupations, although this relationship was not directly cross-analyzed in this project.

<img width="1989" height="738" alt="imagen4" src="https://github.com/user-attachments/assets/2bfd8f11-1d2f-442d-a75a-7196b01145df" />

**Key Insight:** Customers with a Bachelor's degree or a Graduate Degree tend to purchase more bicycles compared to other education levels.

### Are higher-income customers more likely to purchase a bicycle?

The analysis suggests a positive relationship between annual income and bicycle purchases: customers with higher annual incomes tend to purchase bicycles more frequently than lower-income customers. When comparing the overall average income by region, customers in the **Pacific** show the highest average annual income, closely followed by **North America** — although, within North America, the Old age segment records the single highest average value in the entire dataset. Customers in **Europe** show, on average, the lowest annual income of the three regions.

<img width="1992" height="730" alt="imagen5" src="https://github.com/user-attachments/assets/4c3849b3-1cd8-48ea-a35c-8761bddd783c" />

**Key Insight:** Purchasing power appears to be an important factor influencing bicycle purchases. Marketing strategies and product offerings could be adjusted based on the income characteristics of each region.

### How does commuting distance affect customers' purchasing decisions?

Customer purchasing behavior varies based on the distance traveled to work. Most bicycle purchases were made by customers with a commuting distance of 0 to 1 mile, while purchase frequency decreases as commuting distance increases.

<img width="2000" height="805" alt="imagen6" src="https://github.com/user-attachments/assets/bef9cc9e-77c8-4491-8ce7-c8900a8d9255" />

**Key Insight:** The results suggest that bicycles are primarily used as a practical transportation option for short commutes, of up to 1 mile, rather than for long-distance travel.

## 6. Dashboard (Share)

Finally, an interactive dashboard was developed in Microsoft Excel to consolidate the most important findings into a single, easy-to-use interface.

<img width="1823" height="997" alt="imagen7" src="https://github.com/user-attachments/assets/40dc0a33-8f8e-4e5a-a1c9-dd605d56db8b" />

[Dashboard]([https://tu-enlace.com](https://github.com/said16ed/bike-sales-analysis-excel/blob/main/excel-bike-sales-dashboard.xlsx)) 

## 7. Business Recommendations (Act)

Based on the insights obtained from the analysis, several business recommendations can be proposed to improve Bike IShop's marketing strategy and increase sales performance.

**Marketing Strategy**
Focus advertising campaigns on customers between 18 and 60 years old, particularly those with medium to high annual incomes, as they represent the company's primary customer segment. Additionally, marketing campaigns should be adapted according to the purchasing power of customers in different regions.

**Customer Segmentation**
Develop personalized promotions targeting customers employed in Professional and Skilled Manual occupations, since these groups demonstrate the highest purchase rates. Segmenting customers according to demographic and occupational characteristics can improve marketing efficiency and customer engagement.

**Product Strategy**
Promote urban and commuter bicycles designed for customers who travel short distances to work. This strategy aligns with the purchasing behavior observed in the analysis and may increase customer satisfaction while boosting sales.

**Sales Strategy**
Implement region-specific promotional campaigns based on customer demographics, purchasing behavior, and income levels.

## Conclusion

This project demonstrates how Microsoft Excel can be used as an effective business intelligence tool to transform raw data into meaningful insights. The analysis identified several factors that influence bicycle purchasing decisions, including customer age, occupation, education level, annual income, and commuting distance. These findings provide valuable information that can support marketing initiatives, customer segmentation strategies, and business decision-making.
