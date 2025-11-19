# SUPER-STORE-
A detailed Power BI dashboard analyzing Superstore sales, profit, and quantity across regions, states, categories, and sub-categories. Highlights top-performing products, regional sales dominance, profitability trends, and areas needing improvement through maps, charts, and interactive visuals.
1. Data Collection & Understanding

I began by importing the Superstore dataset into Power BI Desktop. The dataset included fields such as Sales, Profit, Quantity, Category, Sub-Category, State, Region, and Year.
I reviewed the data structure, checked for missing values, ensured data types were correct, and confirmed date columns were properly formatted for time-based analysis.

2. Data Cleaning & Preparation

Verified numerical fields (Sales, Profit, Quantity) were correctly recognized as numeric.

Standardized text fields such as Category, Sub-Category, State, and Region.

Ensured relationships were correctly detected—mainly a single flat table, so no complex modeling was required.

Created additional calculated fields when needed (e.g., % Contribution, Year extraction).

3. Designing the Dashboard Layout

I structured the report into multiple pages, each focusing on a specific aspect of analysis:

Page 1: Regional Performance Overview

Created donut charts showing Sales % by Region.

Added bar charts comparing Sales and Profit by Region.

Used a clustered column chart for Sales and Quantity comparison across Central, East, West, and South.

Page 2: Sub-Category Performance

Built bar charts ranking sub-categories by Sales, Quantity, and Profit.

Highlighted top performers like Phones, Chairs, Storage and low-profit segments such as Tables and Bookcases.

Used a scatter plot showing the relationship between Sales and Profit for deeper insight.

Page 3: Category vs. Region

Created a clustered bar chart showing Category-wise sales distribution across regions.

Compared Technology, Furniture, and Office Supplies side by side.

Page 4: State-Level Analysis (Maps)

Used Filled Map visuals to display:

Sales by State

Profit by State

Category distribution across states

Enabled zoom and interaction to analyze geographical performance.

Page 5: Detailed Table Summary

Added a detailed table summarizing:

Sum of Sales

Sum of Profit

Quantity

For every Sub-Category

This helped validate and support the graphical insights.

Page 6: Yearly Trends

Plotted a line chart showing Sales by Year and Region.

Helped identify yearly growth patterns from 2014–2017.

4. Visual Formatting & Enhancements

Applied consistent color themes for clarity (e.g., Region-based colors).

Used data labels, tooltips, and legends to make visuals clearer.

Added slicers for Region, Category, and Year to make the dashboard interactive.

Ensured all visuals aligned properly, maintaining a clean professional layout.

5. Insights Generated

After building the dashboard, several key insights were identified:

Regional Insights

West Region contributed the highest sales (~31%).

South Region consistently showed the lowest performance (~17%).

Sub-Category Insights

Phones and Chairs were top revenue drivers.

Tables, Bookcases, and Supplies showed negative or low profitability.

State-Level Insights

Sales and profit distribution varied widely, with major contributions from states like California, New York, and Texas.

Category Insights

Technology was the highest-earning category overall.

Some Office Supplies segments performed well, but certain items had low margins.

6. Final Validation & Testing

Cross-checked totals with the data model to ensure accuracy.

Validated filters, interactions, and slicers.

Exported visuals and arranged them for presentation-quality reporting.

FINAL OUTCOME

A fully interactive Power BI report providing clear, actionable insights into Superstore Sales, Profit, and Quantity across multiple dimensions—Region, State, Category, and Sub-Category—supported by charts, maps, tables, and trend analytics.
