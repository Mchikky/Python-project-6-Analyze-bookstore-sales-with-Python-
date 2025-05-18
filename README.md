# Project 6: Analyze bookstore sales with Python 
As a Data Analyst consultant at Lapage, originally a physical bookstore with several points of sale. But given the success of some of its products and its customers' enthusiasm, it decided 2 years ago to open an online sales site.

## Objectives 
1. Take stock after two years of operation, analyze its strengths, weaknesses, client behaviors, etc.
2. Analysis of the different sales indicators.
3. A more targeted analysis of customers to understand the behavior of our online customers, to then be able to compare it with the knowledge acquired through our physical bookstores. 
4. Look at certain correlations, the link between a client's gender and the categories of books purchased; the link between clients' age and the total purchase amount, purchase frequency, average basket size, and the categories of books purchased.

### Project Scope: 
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Key Performance Indicators (KPIs)
- Generation of graphics and visuals
- Insights and Recommendations

### Data Preprocessing
- Imported 2 csv. data files (customers and products).
- Studied the data values, checked the columns and rows.
- Filled missing data with zero.
- Joined the 3 csv. data files.
   
### Exploratory Data Analysis (EDA) 
- Summarized the data into total sales by each categories, total profit and the best selling category.
- Checked for the outliers, normality, correlation coefficient, and caluclated zscores.
   
### Key Performance Indicators (KPIs)
1a. Analysis of indicators and charts related to revenue
Examine the key performance indicators related to revenue:
- Total revenue
- Revenue by product or service
- Revenue by region
- Revenue growth

b. Evolution over time and decomposition with a moving average
To evaluate the overall revenue trend, use a time series analysis:
- Graph of monthly/quarterly revenue over a given period
- Use of a moving average (e.g., a 3-month moving average) to smooth out seasonal variations and identify the overall trend.

c. Zoom in on references, top performers, underperformers, and distribution by category
Delve deeper into the analysis by exploring:
- The top-performing and underperforming references
- The distribution of revenue by product or service category
- Comparison of performance between different categories

2a. A more targeted analysis of customer profiles.
Revenue distribution among customers using a Lorenz curve.

b. Examine certain correlations:
- The link between the gender of customers and the categories of books purchased.
- The link between customers' ages and the total amount of purchases, purchase frequency, average basket size, and categories of books purchased.
   
### Generation of graphics and visuals
- Use bar plots for summaries, line graph for trends and scatter plot for relationships.
- Used Lorenz curve for Gini index

### Insights and Recommendations
- There is no need to remove the outliers, the costly goods; there are several ostentatioius goods that are part of the stock 
