# PowerBI_Sales_analysis
**Sales analysis dashboard

Main Themes:
Relational Data Modeling: The core of the system is built upon a relational data model, connecting various entities such as Customers, Orders, Order_Details, Employees, and Products.
This structure facilitates data integrity and efficient querying.

Data Exploration and Transformation:
The interface supports various data operations, including getting data from diverse sources, transforming data, and managing relationships, indicating a robust data preparation workflow.

Customer-Centric Insights:
A significant focus is placed on customer data, including contact information, addresses, and sales representatives, suggesting an emphasis on customer relationship management and targeted analysis.

Sales and Order Performance Analysis:
The dashboard visualizes sales data, specifically "TotalAfterDiscount," broken down by company and product, highlighting performance metrics and potential areas for analysis such as discounts and order quantities.

User-Friendly Interface for Business Intelligence:
The visual cues and menu options ("Home," "Insert," "Modeling," "View," "Optimize," "Help") indicate a user-friendly interface designed for business users to create reports and dashboards.

####
Important Facts:
  1)
  *The data model clearly defines five main entities:
   -Customers.
   -Orders.
   -Order_Details.
   -Employees.
   -Products.

*Relationships are established between these entities:
 -Customers to Orders (one-to-many, via CustomerID).
 -Employees to Orders (one-to-many, via EmployeeID).
 -Orders to Order_Details (one-to-many, via OrderID).
 -Products to Order_Details (one-to-many, via ProductID).


 2)
 * Detailed Customer Data:
   -Customer Table View.
   -Key Customer Attributes.
   -Geographic Diversity.
   -Contact Roles.

3)
*Sales Performance Dashboard:-
 -Total Sales After Discount: A prominent card at the top displays "$1.22M" for "TotalAfterDiscount," representing a key performance indicator.
 -Filters: The dashboard incorporates filters for "Year_Month," "Product Name," and "ShipCountry," allowing users to interactively narrow down the data.
 -Tabular Data View: A table on the left displays "Order ID," "Product Name," "Quantity," "Unit Price," and "TotalAfterDiscount" for individual orders, providing details.
 -Grouped Bar Chart Visualization: A bar chart visualizes "TotalAfterDiscount by Last Name and CompanyName." The "Company/Name" axis shows entities like "Sergientko," "Kotlas,..etc.
 -Values in Visualizations: The "Values" section in the "Visualizations" pane indicates that "TotalAfterDiscount" is a primary measure being used for analysis.
 -Drill-through Capability: The "Drill-through" and "Keep all filters" options suggest that the dashboard is interactive, allowing users to delve deeper into specific data points.
