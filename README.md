# Walmart Black Friday Sales Analysis

## Overview
This project analyzes customer purchase behavior at Walmart during Black Friday sales events. The primary goal is to understand how purchase amounts vary across different customer demographics and other influencing factors, providing actionable insights for business decision-making.

## Business Problem
Walmart Inc.'s management team aims to analyze customer purchase behavior, specifically the purchase amount, against various factors like gender and age. They seek to understand if spending habits differ between male and female customers, particularly whether women spend more on Black Friday than men. (Assuming an equal split of 50 million male and 50 million female customers globally).

## Dataset
The analysis utilizes transactional data collected from customers who purchased products from Walmart Stores during Black Friday.

The dataset includes the following features:
* User_ID: Unique identifier for each customer.
* Product_ID: Unique identifier for each product.
* Gender: Sex of the user (Male/Female).
* Age: Age of the user, binned into categories (e.g., 0-17, 18-25, 26-35, 36-45, 46-50, 51-55, 55+).
* Occupation: Occupation of the user (masked).
* City_Category: Category of the city (A, B, or C).
* Stay_In_Current_City_Years: Number of years the user has stayed in the current city.
* Marital_Status: Marital status of the user (0 for single, 1 for married).
* Product_Category: Product category (masked).
* Purchase: The purchase amount.

## Analysis Highlights & Key Insights

### Data Overview
* The dataset contains 550,068 rows and 10 columns.
* No null values were found.
* The mean purchase amount is approximately $9264.
* There are 5,891 unique customers.
* There are 3,631 unique products.

### Gender-wise Analysis
* Males constitute approximately 75.31% of the customers, while females constitute 24.69%.
* Males generated 76.72% of the total revenue, while females generated 23.28%.
* The average purchase amount per transaction for males is approximately $9437.53, and for females, it is approximately $8734.57.
* On average, each male made a total purchase of approximately $925,438.92, while each female made a total purchase of approximately $712,269.56.
* The population mean of total spending for each male is approximately $925,156.36.
* The population mean of total spending for each female is approximately $711,789.37.

### Marital Status Analysis
* 58% of the unique customers are single, and 42% are married.
* Customers who are single generated 59.05% of the total revenue, while married customers generated 40.95%.
* The average number of transactions for married users is 91, and for single users, it is 95.
* On average, each married customer makes a total purchase of approximately $843,469.79, and each single customer makes a total purchase of approximately $880,526.31.
* The population mean of total spending for each single customer is approximately $880,356.19.
* The population mean of total spending for each married customer is approximately $843,632.08.
* The distributions of total spending for singles and married individuals overlap, suggesting no significant difference in spending habits between these two groups.

### Age Group Analysis
* The majority of transactions (approximately 81.82%) were made by customers aged between 18 and 50 years.
* The age group 26-35 years accounts for the highest percentage of unique customers (34.85%) and generated 39.87% of the total revenue.
* The population mean of total spending for:
    * Age group 0-17: approximately $617,797.25.
    * Age group 18-25: approximately $854,676.31.
    * Age group 26-35: approximately $989,120.36.
    * Age group 36-45: approximately $879,434.88.
    * Age group 46-50: approximately $792,671.74.

### City Category Analysis
* Majority of the total unique customers belong to the city C. Cities B and C combined account for 82.26% of total unique customers.
* Walmart generated 41.52% of the total revenue from the customers belonging to the city B, 32.65% from city C, and 25.83% from city A on Black Friday.

### Product Category Analysis
* The top 5 product categories (1, 5, 8, 6, and 2) account for 84.36% of the total revenue.
* Product Category 1 alone accounts for 37.48% of the total revenue.

### Occupation Analysis
* 82.33% of the total transactions are made by customers belonging to 11 specific occupations (4, 0, 7, 1, 17, 20, 12, 14, 2, 16, 6 in descending order of transaction share).

### Stay in Current City Years Analysis
* 53.75% of total transactions are made by customers who have stayed in the current city for 1 or 2 years.

## Recommendations
Based on the analysis, here are actionable insights for Walmart:

* **Targeted marketing**: Tailor marketing strategies to cater to males' preferences and needs, including specific promotions, product offerings, or advertising campaigns.
* **Focus on popular occupations**: Focus marketing efforts on the 11 specific occupations that generate 82.33% of transactions by understanding their needs and creating targeted campaigns.
* **Engage with new residents**: Engage with new residents (53.75% of transactions from 1-2 years stay) through targeted marketing, welcoming offers, and incentives.
* **Emphasize popular product categories**: Allocate resources and promotions towards the top 5 product categories (1, 5, 8, 6, 2) to maximize sales potential.
* **Increase focus on single customers**: Dedicate efforts to cater to single customers (59.05% of total revenue) by understanding their motivations and targeting them with personalized offers.
* **Competitive pricing and promotions**: Continuously monitor competitors' pricing and promotional activities and consider offering price-match guarantees.

## Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
