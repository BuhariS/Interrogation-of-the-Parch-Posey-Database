# Interrogation of the Parch & Posey's (P&P's) Database to Improve its Business Performance¶
by
Buhari Shehu (The Datavestigator)
shehubuhari1@gmail.com

<img src="erd.png" width=700 height=200 />

## Overview
Improving business performance is often a priority for companies in order to remain competitive and achieve long-term success. This can involve conducting regular assessments of the business's strengths and weaknesses, setting clear goals and objectives, and implementing targeted strategies to address any identified areas for improvement. Parch and Posey (P&P) are seeking to improve their business performance in order to remain competitive and achieve their overall business goals. To this end, a database analysis was conducted using SQL and Pandas to uncover insights about P&P's performance. The mode of inquiry adapted for this project involved posing questions, querying the database, organising the data into dataframes, visualising the results, and drawing insights. The business goal was broken down into three objectives: productivity, revenue, and growth. These were examined through the lenses of sales representatives, customers, products, channels, regions, and growth. The findings showed that P&P has strong customer retention and growth rates. However, there is room for improvement in terms of revenue growth, and the project provides recommendations for how this can be achieved.

## Introduction
P&P is a fictitious paper company that sells three types of papers to their customers drawn from the Fortune 500 through various advertising channels. It has 50 sales representatives spread across four regions of operation in the United States (US).

The goal of this project is to examine P&P's productivity, revenue, and growth objectives. To achieve this, we will use SQL, Pandas, and visualization tools to analyze the P&P database (supplied by Udacity) and extract insights. Our ultimate objective is to assist P&P in its decision-making process and align its employees' efforts towards realizing its business goals.

The project file is titled `"Interrogation of the Parch & Posey Database.ipynb"` while the database is titled `pandp.db`

### Project File 
The project in this repository resides in the "Interrogation of the Parch & Posey Database.ipynb" file.

## Methodology
To accomplish the goal of this project we will follow these steps:
1. Ask a question
2. Query the database
3. Transform query output to a Pandas DataFrame (occasional)
4. Visualise the Pandas data (occasionally)
5. Extract insights

## Dependencies
To ensure the successful execution of this project, it is crucial to have the following listed packages installed:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sqlalchemy`
- `ipython-sql`
- `pymysql`

## Conclusions
- P&P has excellent employee retention strategies, which leads to cost savings on hiring expenses.
- The top-performing sales reps recorded up to or close to a million USD in total sales.
- Most of the top performers showed consistent growth, with exceptional performance in 2016.
- The top performers appear to be in close competition with one another.
- The low-performing sales reps recorded less than 150 thousand USD in total sales.
- Some of the low-performing sales reps are new employees.
- Five of the bottom customers have less than $1,500 in cumulative spending to date. Their low spending may be due to the fact that some of them are new or have churned.
- The direct channel, Northeast region, and standard paper product category generate the most revenue.
- The best year for the company was 2016, with an annual growth rate of 123%.

## Recommendations
Based on the outcome of the project the following are recommended:
- By offering incentives to the top performers, P&P can encourage other team members to strive for similar levels of success. Additionally, promoting top performers to mentor other team members can help to spread their knowledge and expertise, leading to improved sales performance across the organisation.
- Consider conducting interviews with low-performing sales reps to uncover any challenges they may be facing.
- Encourage top customers with discounts and dedicated support in order to increase customer loyalty and satisfaction.
- Attempt to contact churned customers with the goal of bringing them back to the business.
- Invest more in the direct channel and Northeast region, and investigate why other channels and regions are not performing as efficiently.
- Utilise the minimum, maximum, average, and monthly number of orders data for each paper product in order to optimise inventory management.
- Look for ways to build upon the business success of 2016 in order to drive further growth.
