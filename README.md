# Walmart Black Friday Sales Analysis

## Business Problem
Walmart's management team wanted to understand whether purchase behaviour 
differs significantly across customer demographics during Black Friday. 
The key question: do male and female customers spend differently, 
and which segments drive the most revenue?

## Dataset
- Source: Kaggle — Walmart Black Friday transactional data
- Size: 550,068 rows × 10 columns
- Key fields: Gender, Age group, Occupation, City category, 
  Marital status, Product category, Purchase amount

## Tools Used
Python · Pandas · NumPy · Matplotlib · Seaborn · SciPy

## Project Workflow
1. Data loading and quality checks (null values, duplicates, data types)
2. Univariate analysis — distributions for each variable
3. Bivariate analysis — purchase patterns by gender, age, city, occupation
4. Statistical inference — Central Limit Theorem used to estimate 
   population-level spending means from sample data
5. Business recommendations derived from findings

## Key Findings
- Male customers account for 76.7% of total revenue vs 23.3% for female
- The 26–35 age group generates 39.9% of total revenue
- Single customers spend ~4% more per head than married customers
- Top 5 product categories account for 84% of all revenue
- City B generates the highest revenue (41.5%), despite City C having 
  more unique customers

## Business Recommendations
- Target the 26–35 male demographic with personalised Black Friday 
  campaigns — highest revenue segment
- Focus marketing on 11 specific occupation groups generating 82% 
  of all transactions
- Incentivise female shoppers — currently underrepresented at 24.7% 
  despite equal population split
- Promote top 5 product categories more aggressively in pre-event campaigns
- Invest in City B infrastructure and logistics — highest revenue location
