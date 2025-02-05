# Adventure-Works-Analysis

This project explores the factors driving the strong sales of bikes, focusing on both product performance and external influences. The bike category has seen consistent success, with several contributing factors such as customer demographics, weather conditions, and urban commuting trends. Customers with higher disposable incomes, like those with bachelor’s degrees and professional occupations, are more likely to invest in bikes, but weather patterns also play a significant role in demand. Seasonal changes, such as warmer months, lead to increased sales, while adverse weather may impact purchase decisions. Additionally, the growing emphasis on health, fitness, and eco-friendly transportation options has made bikes an attractive choice for many. The project aims to analyze these diverse factors and recommend strategies to optimize product offerings and marketing efforts.

## Data Source
The data set used for this project was gotten from kaggle.com

## Problem Statement
The problem statement was generated base on four category

- **Customer Problem Statement**
- **Product Problem Statement**
- **Time Series Problem Statement**
- **Geography Problem Statement**

### Customer Problem Statement

- Are there significant different in spending patterns between Male and Female Customer and which category generate the highest Revenue.
- How does revenue vary between single and married and which group contribute the most in sales.
- How does Revenue generation differ amoung customers with different Occupation and which Occupational Level contribute the most in the over all sales.
- Which Income Group category contribute the most in Revenue and how does the spending behaviour vary across the different category.
 
### Product Problem Statement

- Which Product Category contribute the most to total Revenue.
- Which Product Category has the highest Return Rate and what could be the possible common reason behind the returns
 
### Time Series Problem Statement

- How has Revenue evolued across different time periods and what trends and seasonal patterns impact over all time sales performance.
- How has Customers change overtime and what possible factor contribute to period growth.
- How do orders volumn change over time across different time interval
 
### Geography Problem Statement
- Which Country / Region contribute the higest Revenue

## Tool Used
- Python (jupyter notebook)

## Skills Demonstrated
- Data cleaning
    which involues
   - Adding addtion column for measure calculation
     
     ![](data_cleaning_adding_columns.png)
     
   - Removing null values
     
     ![](data_cleaning_null_values.png)
     
   - Converting data type

     ![](data_cleaning_data_types.png)
     
   - Removing unwanted columns

     ![](data_cleaning_removing_columns.png)
     
- Data Analysis

## Data Analysis & Findings
**Customer Findings**
- Revenue analysis based on customer gender reveals no significant difference in spending patterns between male and female customers. Both genders contribute almost equally to total sales, with female sales trailing male sales by just 0.8%.
- Revenue analysis based on marital status shows that married customers generate $12.9M out of the total $24M in revenue, surpassing single customers, who contribute $12.0M, by 3.6%.
- Customers with professional occupations generate the highest revenue, contributing $8.5M (34.0%) of the total revenue. typically falling between low-income and average-income earners, this group shows a strong preference for bikes, which is the top-selling product.

**Product Findings**
- The bike category dominates sales, generating 94.9% of total revenue across its three categories. Spreading its sales across its subcategory, Mountain bikes which contribute the highest revenue at $18.6M, followed by road bikes at $11.2M, and touring bikes at $3.8M.
- Although bikes account for 94.9% of total sales, accessories rank as the most returned product category, making up 61% of all returns. The overall return rate remains low at 2.17%.

**Time Series Findings**
- Sales experienced a significant year-over-year (YoY) increase of $2.9M (45.6%) from 2020 to 2021. From 2021 to 2023, sales continued to grow steadily and are forecasted to keep rising due to strong performance in the first half of 2023. However, the absence of sales data for the second half of 2023 prevents an accurate YoY comparison for that year.
- Customer acquisition has grown significantly each year, with 309 new customers added between April 2020 and April 2021, followed by a massive increase of 5,000 new customers by April 2023. This surge in customer base has directly contributed to a significant rise in sales.
- The significant increase in customers has directly driven a 98% surge in orders, reflecting higher purchasing activity.

**Geography Findings**
- North America generates the highest sales revenue among all continents, totaling $9.7M. Within the continent, the United States contributes the majority of sales, accounting for $7.9M.

## Over All Insight

In the Time Series Analysis, there are certain splik in sales and this are my three reasons

**Weather Condition**

Bike Product generate 94.9% in top countries like US, UK, and Austrialia
During the spring Period (April, May and June) in the northern hermisphere **Road Bike** are more popular because people return to cycling after winter.
In the northern(United State) and southern(Austrialia, UK, Germany) hermisphere during summer period (June, July and August) (December, January and Feburary) which is relatively hot, warm season **Moutain Bikes** and **Tourist Bike** become more popular as people will take advantage of summer condition to explore rougher terrians and embark on longer cycing tour.
During the fall season in the sourthern hermisphere **Moutain Bikes** is an excellent time for fall seasons

**Increase in Customer**

Has leads turns into customers there is an increase in orders which significantly lead to an increase in sales. The customer increased from 931 in April 2021 to 5934 in April 2022

**Customer Income**

Using a violin plot, there is more density in customer with low and average income compared to high income, noting that Bikes contribute 96.9% in sales customers with average and low income often purchases Bike for
 - Afforability and Cost Efficient
 - Leisure and Recreation
 - Eco-Friendly Transportation

