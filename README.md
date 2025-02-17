# Real Estate Data Analysis
## Project Overview
This project involves a comprehensive analysis of real estate data to give meaningful insights, uncover trends, and patterns. The real_estate dataset includes information such as property sales, assessed values, towns, addresses, and property types. The analysis aims to answer key questions about sales trends, property values, and market behavior using Python.
## Analysis Steps
#### 1. Data Cleaning and Preparation
- Removed unnecessary columns: Columns that were not relevant to the analysis were dropped to streamline the dataset.

- Handled missing or unknown values: Rows with '***Unknown***' in the 'Town' column were identified and replaced with the correct town names using the address information.

- Changed data types: Ensured that columns like 'Sale Amount' and 'Assessed Value' were converted to numeric types for accurate calculations.

#### 2. Key Metrics and Trends
- Sales Trends: Analyzed the number of properties sold over time to identify trends in sales volume.

- Average Sales for Each Town: Calculated the average sale amount for properties in each town to understand market differences.

- Average Assessed Value for Each Town: Determined the average assessed value of properties in each town to compare with sale amounts.

- Total Sale Volume: Computed the total sales volume across all properties to gauge the overall market activity.

- Properties Sold Each Year: Counted the number of properties sold in each year to track market activity over time.

- Property Type with the Most Sales: Identified the property type (e.g., single-family homes, condos) that had the highest number of sales.

- Correlation Between Assessed Value and Sale Amount: Analyzed the relationship between assessed values and sale amounts to determine if assessed values are a good predictor of sale prices.

- Growth Rate of Assessed Values: Calculated the measure of change or growth rate in assessed values over time to understand property value appreciation.

#### Insights
1. Sales Trends
Over the years, the number of properties sold has shown fluctuations, with a peak in 2021.

2. Town-Level Analysis
Town Willington had the highest average sale amount, while Stafford had the lowest. And The average assessed value was significantly higher in Greenwich, indicating a more expensive market.

3. Property Types
Single-family homes were the most sold property type, accounting for 67.45% of total sales.

4. Assessed Value vs. Sale Amount
A weak correlation was found between assessed values and sale amounts, indicating that assessed values are not a reliable predictor of sale prices.

 Assessed values have grown at an average rate of 5.62% per year, with the highest growth observed in Public Utility at 300.00%.

#### Recommendations
Buyers can focus on single-family homes if looking for a property type with high resale activity.

while For Sellers Properties in Town Willington can command higher sale amounts, making it an ideal market for sellers.

Investors can Invest in condos due to their high growth rate in assessed values and increasing demand.

For Policymakers Address the disparity in assessed values and sale amounts across towns to ensure fair property taxation.

Promote development in towns with lower sales activity to stimulate the real estate market.

Tailor marketing strategies to the specific needs and demographics of each town. For example, focus on luxury buyers in high-value towns like Greenwich and affordable housing in lower-value towns.

Implement incentives for first-time homebuyers or affordable housing programs in towns with lower sales and assessed values to stimulate the market.

#### Code and Data
The full analysis code can be found in the Jupyter Notebook: real_estate_analysis.ipynb.

The dataset used for this analysis is available in : <a href="https://catalog.data.gov/dataset/real-estate-sales-2001-2018">RE_DATA</a>


