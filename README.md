# Housing-Data-Analysis

# 1. Objective
The purpose of this project is to analyze a housing dataset to:
● Determine the average, minimum, and maximum house prices
● Identify structural and feature-based patterns influencing pricing
● Explore the relationship between property area, number of bedrooms, and house pricing
● Support predictive insights and guide prescriptive strategies for pricing and development
focus

# 2. Project Overview
This project involved analyzing a dataset with 378 housing records across 13 variables using
Microsoft Excel. The variables include 6 numerical features (e.g., price, area, bedrooms) and 7
categorical features (e.g., basement, air conditioning, furnishing status). We performed
descriptive, diagnostic, predictive, and prescriptive analytics using Excel techniques such as
PivotTables, formulas, charts, correlation, and regression.

# 3. Methodology
A. Data Cleaning
● Column Adjustments: Used auto-fit for better visibility (manual and VBA method).
● Filter Application: Enabled filters to inspect specific features like mainroad or
guestroom (none found).
● Duplicates: No duplicate records found.
● Blank Cells: Checked using filters and 'Go To Special' function; none found.
● Formatting: Bolded headers and froze the top row. Structured the dataset as a table for
analysis readiness.

# B. Exploratory Data Analysis (EDA)

![image](https://github.com/user-attachments/assets/311223a7-2ddd-405f-8496-cfabbb8230fb)
![image](https://github.com/user-attachments/assets/c7c08326-fc10-4798-9890-c838778c0707)

i. Numerical Summary
● Price:
○ Max: GHS 13,300,000.00
○ Min: GHS 1,750,000.00
○ Average: GHS 4,767,740.19
○ Total Income: GHS 1,802,205,790.00
● Area:
○ Max: 16,200 sq ft
○ Min: 1,700 sq ft
○ Average: 5,264 sq ft
Bedrooms:
○ Max: 6 | Min: 1 | Average: 3
● Other Features:
○ Bathrooms, Stories, Parking all range from 1–4 with averages of 1–2 units

ii. Categorical Summary (PivotTable Counts)
Feature Yes No
Basement 102 276
Hotwater Heating 17 361
Air Conditioning 115 263
Preferred Area 89 289
Furnishing Status Furnished:98
Semi: 157

iii. Price Ranges
Low Price: 254 homes
Medium Price: 117 homes
High Price: 7 homes

# 4. Data Visualization 
![image](https://github.com/user-attachments/assets/dfd34c01-9cca-4b14-ab82-c7383c4fa227)
![image](https://github.com/user-attachments/assets/0d986e69-d4c6-4fd2-8429-e1fd2dfda5f9)
Visuals Included:
Bar chart of Price Range
Scatter Plot: Area vs Price (with trendline & R² = 0.2691)
Bar chart: Air Conditioning Status across Price Ranges
KPIs: Max Area, Low Price House Count, Air-conditioned Homes
Pie charts: AC and Prefarea status
Column charts: Furnishing distribution
Regression trendline chart: Area vs Price


# Story:
 The majority of homes (67%) fall into the low-price category. Despite the highest area being 16,200 sq ft, many large-area houses remain in lower price brackets. Air conditioning is present in 115 homes, most of which are medium-to-high priced. There is a weak positive correlation between area and price (R² = 0.2691), suggesting that area alone is not the dominant driver of price.

5. Data Analysis
Correlation Analysis
Price vs Area: Weak positive correlation (r ≈ 0.52)
Price vs Bedrooms: Mild relationship
Interpretation: Area influences price more than number of bedrooms but is not a sole factor.
Price Categories using IF Logic
Used Excel IF statements to classify homes:
Low: < GHS 3,000,000
Medium: 3M–8M
High: > 8M
Used PivotTables to explore how features like AC, preferred area, and furnishing status vary across price bands.

# Story:
 Higher-priced homes tend to have air conditioning, be in preferred areas, and be furnished. Regression analysis shows an R² of 0.2691, indicating a weak model fit but still helpful in predicting general trends.

# 7. Results – Full Data Story
The dataset reveals that the majority of houses are priced below GHS 3 million. Factors such as AC, preferred area, and furnishing increase the likelihood of higher pricing. However, area alone does not strongly dictate price. The average home has 3 bedrooms, 1 bathroom, and minimal luxury features.
Predictive modeling indicates that price trends are not affected by area; other factors significantly influence final pricing. The most valuable homes tend to be fully equipped and well-located.

# 8. Discussion & Conclusion
# Insights:
Developers should invest in comfort features (AC, furnishing) and location selection (preferred areas) for value addition.
The majority of homes are underpriced due to a lack of features.
Regression is useful, but should be supported by feature scoring or advanced modeling for stronger predictions.

# Recommendations:
Add a guestroom and improve heating systems to increase value
Target developments with more premium features for preferred area properties
Use What-If Analysis for development planning (e.g., how much area to achieve the target price)





