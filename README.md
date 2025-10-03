# Superstore Sales Analysis Dashboard

## 1. Project Objective

The goal of this project was to create a simple, interactive sales dashboard using Power BI. The dashboard analyzes the provided Superstore_sales.csv dataset to reveal key performance indicators related to sales by region, product category, and time.

## 2. Tools Used

* *Power BI:* For data visualization and dashboard creation.
* *Microsoft Excel/Text Editor:* For initial data review and drafting insights.

## 3. Process

1.  *Load Data:* The Superstore_sales.csv dataset was imported into Power BI.
2.  *Data Transformation: In the Power Query Editor, a new Month-Year column was created from the Order Date column to enable time-series analysis.
3.  *Visualization:* Three core visuals were created:
    * A *line chart* to show sales trends over months.
    * A *bar chart* to compare sales performance across different regions.
    * A *donut chart* to show the sales distribution by product category.
4.  *Interactivity: A *slicer* was added to allow users to filter the entire dashboard by region.
5.  *Styling: *Conditional formatting* was used to highlight the top-performing region and make the dashboard clean and easy to read.

## 4. Key Insights

The analysis of the superstore sales data revealed the following key insights:

* *Insight 1: Regional Performance Dominance*
    The *West region* is the clear leader in sales, outperforming all other regions. Highlighting this area can help focus marketing and inventory management efforts.

* *Insight 2: Top Product Category*
    The *Technology* category is the most significant driver of revenue, accounting for the largest portion of total sales. This indicates a strong market for tech products.

* *Insight 3: End-of-Year Sales Peak*
    Sales show a consistent and strong upward trend in the last quarter, peaking in *November*. This pattern is crucial for planning promotions, staffing, and inventory for the holiday season.

*(A plain text version of these insights can also be found in the Key_Insights.txt file.)*

## 5. Files in this Repository

* superstore_sales.pbix: The main Power BI project file containing the full interactive dashboard, data model, and queries.
* Superstore_sales.pdf : A PDF export of the final sales dashboard for a quick, static view.
* Superstore_sales.csv : The raw dataset used for this analysis.
* Key_Insights.txt: A plain text file containing the key findings from the dashboard.
