# Data Dictionary

## Overview
This document describes the structure and contents of the sample dataset used in the Sales & Customer Analytics Dashboard.

## Tables

### Sales Data
| Field Name | Data Type | Description | Example |
|------------|-----------|-------------|---------|
| Order_ID | String | Unique identifier for each order | ORD-2023-001 |
| Order_Date | Date | Date when order was placed | 2023-01-15 |
| Customer_ID | String | Unique customer identifier | CUST-123 |
| Customer_Name | String | Full name of customer | John Smith |
| Category | String | Product category | Technology |
| Subcategory | String | Product subcategory | Phones |
| Product_Name | String | Name of product | Samsung Galaxy S23 |
| Sales | Decimal | Total sales amount | 999.99 |
| Quantity | Integer | Number of units sold | 2 |
| Profit | Decimal | Profit from transaction | 150.00 |
| Discount | Decimal | Discount percentage | 0.10 |
| Region | String | Geographic region | West |
| State | String | US State | California |
| City | String | City name | Los Angeles |

## Data Notes

- **Date Range**: January 1, 2023 - December 31, 2023
- **Currency**: USD ($)
- **Records**: Approximately 9,000+ transactions
- **Customers**: 693 unique customers
- **Products**: 3 main categories, 17 subcategories
- **Geographic Coverage**: 4 regions, 49 states, 500+ cities

## Categories

### Technology
- Phones
- Copiers
- Machines
- Accessories

### Furniture
- Chairs
- Tables
- Bookcases
- Furnishings

### Office Supplies
- Binders
- Storage
- Paper
- Appliances
- Envelopes
- Fasteners
- Labels
- Supplies
- Art

## Geographic Hierarchy

### Regions
- East
- West
- Central
- South

## Data Quality Notes

- No missing values in key fields
- All dates are valid and within expected range
- Profit calculations: Profit = Sales - (Cost + Discount)
- Dummy data generated for portfolio demonstration
