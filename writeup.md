Sales Comparison by Region using Tableau
Introduction

This project aims to create an interactive dashboard in Tableau to visualize and compare sales performance between two user-defined regions. This information will be instrumental for the upper management of a hypothetical leading organization to understand regional trends and identify areas for improvement.

Objective

The primary objective of this project is to develop a user-friendly dashboard that allows for the selection and comparison of sales data from two specific regions. This will enable management to gain insights into regional sales performance and make informed strategic decisions.

Data Source

The primary data source for this project is the readily available "Sample Superstore" dataset provided by Tableau. This dataset offers a comprehensive set of sales-related information, including product details, customer demographics, and order data.

Methodology

Data Preparation:

The "Sample Superstore" dataset was loaded into Tableau.
A hierarchy named "Location" was created to categorize regions within countries for a more granular view.
User Interaction:

Two user-defined parameters, "Primary Region" and "Secondary Region," were created. These parameters allow users to select the specific regions they wish to compare.
Calculated Fields:

Calculated fields were created for both the "Primary Region" and "Secondary Region" selections. These fields dynamically filter the data based on user-selected parameters.
Date Consideration:

A calculated field named "First Order Date" was generated to capture the date of the first order, providing a valuable reference point for analyzing sales trends.
Dashboard Design:

All sheet elements were meticulously aligned to ensure a visually appealing and well-organized dashboard.
Data Visualization:

The dashboard is divided into sections, each displaying key sales metrics for the chosen primary and secondary regions. These metrics include:
First Order Date: Provides context for subsequent sales trends.
Total Sales: Quantifies the overall sales performance for each region.
Average Sales per Order: Indicates the average order value for each region.
Number of Customers: Highlights the customer base within each region.
Number of Orders: Shows the total number of orders placed in each region.
Number of Products in Sale: Captures the product diversity offered within each region.
Results

The resulting dashboard provides a comprehensive and interactive overview of sales performance for two user-selected regions. Users can easily compare various metrics, such as total sales, average order value, customer base, and product variety, to identify strengths and weaknesses in each region.

Future Enhancements

Integrate sales data from an external source for real-world application.
Include visualizations like bar charts, line graphs, or maps for more diverse data exploration.
Develop additional calculated fields to analyze specific sales trends or customer segments within each region.