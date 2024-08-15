# PowerBI-Sales-Insights
This repository contains my first project using Power BI, where I developed an interactive and insightful sales dashboard. The dashboard provides a comprehensive analysis of sales data to help stakeholders make informed business decisions.The purpose of the project is to provide information on the company's performance over the past few years, detailing customers, profits, costs, and even predicting future behaviors to make better decisions. The main objective is to present sales information in a clean manner to facilitate understanding through an attractive and easy-to-read report for the user.

### Project Development
The first thing done upon receiving the information was to review all the tables to become familiar with the database. In the first phase, relevant data for the analysis was collected, followed by a thorough cleaning to present a clean report without unnecessary information. The data was normalized to improve the analysis and avoid future confusion or problems. A relational data model was created, establishing primary and foreign keys.

![Diagram E/R](https://github.com/PalomaOrtizM/PowerBI-Sales-Insights/blob/main/Images/Diagram.PNG)

A brief description was added to each table so that the user can understand what each one is about and what information it contains. Columns were deleted and created both in Power BI Desktop and in Power Query to streamline the analysis and the creation of measures.


In the second phase, the project's Mock Up was created in Google Slides, outlining how the required information will be presented. All the necessary measures that would be useful later in the creation of the dashboard were made. For the calculation of measures, it was also necessary to first create calculated columns to facilitate the measures.

In the third phase, visualizations began once the measures were in place and the specified tasks were completed. Data continued to be cleaned, the load of some tables was disabled, a calendar table was determined, all to improve the requested analysis. Finally, the dashboard, visualizations, buttons, titles, and colors were improved to facilitate the reader's understanding.

I created the general page, where we can see some KPIs, different types of graphics to see the main information and numbers.
To the left I added buttons to navigate thrugh the different pages.
![General[]()](https://github.com/PalomaOrtizM/PowerBI-Sales-Insights/blob/main/Images/General.PNG)

## Gross and Net Profit by Category and Subcategory (2013)

### Graph Description 
The graph is a bar chart that compares **gross profit** and **net profit** across three bicycle subcategories:

- **Mountain Bikes**: Have the highest gross profit, reaching approximately $3 million, while the net profit is lower, around $2 million.
- **Road Bikes**: Show a gross profit close to $2 million, with a net profit slightly above $1 million.
- **Touring Bikes**: Have the lowest values among the three categories, with a gross profit just below $2 million and a net profit around $1 million.


![Net Profit and Gross Profit](https://github.com/PalomaOrtizM/PowerBI-Sales-Insights/blob/main/Images/Venta%20por%20categoria.PNG)

### Key Observations

- **Net profit** is consistently lower than **gross profit** for all subcategories.
- This graph allows users to select different years, categories, and subcategories for analysis.

This analysis can be useful for understanding the relationship between gross and net profit in the bicycle market and for making informed decisions about resource management and optimization within these subcategories.


At the end, we were asked to create a calculation group to optimally display the United States segment, also allowing segmentation by product categories and years. We were also asked for a field parameter with different measures to function as a slicer for our customer map by country.


