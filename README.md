<img width="1983" height="793" alt="Panoramico GitHub" src="https://github.com/user-attachments/assets/802753eb-cdab-4f02-a527-e052c691e843" />

# 🚲 Bike Shop Sales Analysis | Excel Dashboard

# 1. Project Description

This project presents an interactive dashboard developed in Microsoft Excel to analyze the purchasing behavior of customers from a fictional bicycle retail company called **Bike IShop**.
The objective of the analysis is to identify the demographic, economic, and social factors that influence customers' purchasing decisions. Based on these findings, business recommendations are provided to help improve marketing strategies and support data-driven decision-making.
The project follows the six phases of the **Google Data Analytics Professional Certificate** framework:

- Ask
- Prepare
- Process
- Analyze
- Share
- Act

# 2. Business Problem (Ask)

Bike IShop is a bicycle retail company operating in multiple regions. Recently, the company has experienced a decline in bicycle sales and wants to better understand which customer characteristics have the greatest influence on purchasing decisions. By analyzing customer data, the company aims to identify opportunities to improve its marketing strategy, better segment its customers, and increase sales. To achieve this objective, the following business questions were defined:

- Which age group purchases the most bicycles?
- Which occupations have the highest purchase rate?
- Does education level influence bicycle purchases?
- Are higher-income customers more likely to purchase a bicycle?
- How does commuting distance affect customers' purchasing decisions?

## Project Objective

Develop an interactive dashboard in Microsoft Excel to analyze customer purchasing behavior and identify the key factors that influence bicycle purchases, providing valuable insights to support business decision-making.

# 3. About the Dataset (Prepare)

This project uses a fictional dataset published by **Alex The Analyst** on GitHub.
The dataset contains demographic and socioeconomic information about customers, including:

- Age
- Gender
- Marital Status
- Education
- Occupation
- Annual Income
- Number of Cars
- Commute Distance
- Region
- Bicycle Purchase Decision

The dataset is intended exclusively for educational purposes and portfolio development.

[Dataset](https://github.com/said16ed/bike-sales-analysis-excel/blob/main/bike-sales-dataset.xlsx)

# 4. Data Cleaning (Process)

Before performing the analysis, the dataset was cleaned and prepared to ensure data quality and consistency. The main data cleaning tasks included:

- Reviewing the dataset for missing or incomplete values.
- Verifying data consistency.
- Standardizing categorical values.
- Correcting formatting inconsistencies.

Several categorical variables were standardized to improve readability:

### Marital Status

- M → Married
- S → Single

### Gender

- M → Male
- F → Female

Additionally, the **Commute Distance** column was standardized by replacing the value **"10+ Miles"** with **"10 Miles +"** to maintain a consistent sorting order within Pivot Tables.

Finally, a new variable called **Age Brackets** was created to classify customers into three age groups:

- Adolescent (Under 18 years old)
- Middle Age (18–60 years old)
- Old (Over 60 years old)

This classification was created using an IF function, allowing customers to be automatically grouped according to their age.

# 5. Data Transformation and Modeling (Process)

After completing the data cleaning process, the dataset was organized and structured to facilitate analysis using Pivot Tables and Pivot Charts in Microsoft Excel. Several Pivot Tables were created to answer the business questions defined at the beginning of the project. Each visualization was designed to identify customer purchasing patterns and provide meaningful business insights. The main variables analyzed include:

- Gender
- Age Brackets
- Occupation
- Annual Income
- Region
- Commute Distance
- Purchased Bike

These variables were combined to compare customer behavior across different demographic and socioeconomic segments.

# Data Visualizations

## Bicycle Purchases by Gender

A bar chart was created to compare bicycle purchases between male and female customers. This visualization helps determine whether gender influences purchasing behavior and identifies which group has the highest purchase rate.

<img width="705" height="404" alt="image_1" src="https://github.com/user-attachments/assets/4602dfb9-4ab9-4c32-9ecf-ecac07adb114" />

## Bicycle Purchases by Commute Distance

Customer purchasing behavior was analyzed based on the distance they travel to work. The objective of this analysis is to determine whether commuting distance affects the likelihood of purchasing a bicycle.

<img width="977" height="256" alt="image_2" src="https://github.com/user-attachments/assets/f77f434d-6804-491e-9d68-134e70853eb6" />

## Bicycle Purchases by Age Group

Customers were grouped into different age categories to identify which segment purchases the most bicycles. This visualization highlights the age group that represents the company's primary target market.

<img width="919" height="261" alt="image_3" src="https://github.com/user-attachments/assets/aa5b1c5d-6bb7-4523-8c44-fb55cedcfade" />

## Average Income by Region

The average annual income of customers was analyzed across different regions. This comparison provides insights into regional purchasing power and helps identify markets with greater sales potential.

<img width="749" height="368" alt="image" src="https://github.com/user-attachments/assets/b6e2af02-8108-4ed7-8f69-7fab0c552c54" />


# Key Performance Indicators (KPIs)

To provide a high-level overview of the dataset, the following key metrics were calculated:

- Total Customers
- Total Bicycle Buyers
- Average Customer Age
- Average Annual Income
- Average Commute Distance

These KPIs provide a quick summary of customer characteristics and support the interpretation of the dashboard's visualizations.

# 6. Interactive Dashboard (Share)

An interactive dashboard was developed in Microsoft Excel to consolidate the most important insights into a single, user-friendly interface. The dashboard includes interactive slicers that allow users to dynamically filter the information by:

- Marital Status
- Region
- Education
- Occupation

This functionality enables users to explore the data from multiple perspectives and supports more effective business decision-making.

## Dashboard

<img width="943" height="561" alt="Dashboard" src="https://github.com/user-attachments/assets/1f4a5954-3459-411c-83a5-b6ec10978b05" />

- # 7. Exploratory Data Analysis (Analyze)

Using the interactive dashboard, the dataset was explored to identify customer purchasing patterns and answer the business questions defined at the beginning of the project. The analysis focused on demographic, socioeconomic, and behavioral variables to better understand the factors influencing bicycle purchases.

# Business Questions

## Which age group purchases the most bicycles?

The analysis shows that customers in the **Middle Age (18–60 years old)** category represent the largest group of bicycle buyers. In contrast, customers classified as **Old (over 60 years old)** have a significantly lower purchase rate, while no bicycle purchases were recorded for the **Adolescent** group.

### Key Insight

The company's primary target market consists of customers between **18 and 60 years old**, making this age group the most attractive segment for future marketing campaigns.

## Which occupations have the highest purchase rate?

The dashboard indicates that customers working in **Professional** and **Skilled Manual** occupations account for the highest proportion of bicycle purchases. Among these groups, professionals represent the largest number of buyers.

### Key Insight

Customers employed in professional and technical occupations appear to have a greater likelihood of purchasing bicycles, making them valuable target segments for future promotional campaigns.

## Are higher-income customers more likely to purchase bicycles?

The analysis suggests a positive relationship between annual income and bicycle purchases. Customers with higher annual incomes tend to purchase bicycles more frequently than lower-income customers. Additionally, customers located in **Europe** have the highest average annual income compared to those in **North America** and **Pacific**.

### Key Insight

Purchasing power appears to be an important factor influencing bicycle purchases. Marketing strategies and product offerings could be adjusted based on the income characteristics of each region.

## How does commute distance affect bicycle purchases?

Customer purchasing behavior varies according to the distance traveled to work. Most bicycle purchases were made by customers with relatively short commuting distances, while purchase frequency decreases as commuting distance increases.

### Key Insight

The results suggest that bicycles are primarily used as a practical transportation option for short-distance commuting rather than long-distance travel.

# 8. Business Recommendations (Act)

Based on the insights obtained from the analysis, several business recommendations can be proposed to improve Bike IShop's marketing strategy and increase sales performance.

## Marketing Strategy

Focus advertising campaigns on customers between **18 and 60 years old**, particularly those with medium to high annual incomes, as they represent the company's primary customer segment. Additionally, marketing campaigns should be adapted according to the purchasing power of customers in different regions.

## Customer Segmentation

Develop personalized promotions targeting customers employed in **Professional** and **Skilled Manual** occupations, since these groups demonstrate the highest purchase rates. Segmenting customers according to demographic and occupational characteristics can improve marketing efficiency and customer engagement.

## Product Strategy

Promote urban and commuter bicycles designed for customers who travel short distances to work. This strategy aligns with the purchasing behavior observed in the analysis and may increase customer satisfaction while boosting sales.

## Sales Strategy

Implement region-specific promotional campaigns based on customer demographics, purchasing behavior, and income levels. Using data-driven segmentation can improve resource allocation and maximize marketing effectiveness.

# Conclusion

This project demonstrates how Microsoft Excel can be used as an effective business intelligence tool to transform raw data into meaningful insights. The analysis identified several factors that influence bicycle purchasing decisions, including customer age, occupation, annual income, and commuting distance. These findings provide valuable information that can support marketing initiatives, customer segmentation strategies, and business decision-making.Overall, the dashboard enables stakeholders to better understand customer behavior and make more informed, data-driven decisions.
