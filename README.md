
readme_content = """# Lilly Tours and Travels - Travel Dashboard

## Project Overview
This project is an interactive Power BI dashboard developed to analyse travel bookings, customer details, revenue, and tour packages.

## Key Features
- Total Customers and Revenue Analysis
- Monthly Booking Trends
- Customer Analysis by State
- Booking Source Analysis
- Customer Payment Mode Analysis
- Tour Package Performance
- Main Travel Destination Analysis
- Booking Status and Trip Type Filters

## Tools Used
- Microsoft Power BI
- Data Visualization
- Data Analysis

## Objective
To analyse travel booking data, understand customer preferences, monitor revenue, and generate meaningful business insights.
"""

with open("README.md", "w", encoding="utf-8") as file:
    file.write(readme_content)

print("README.md file created successfully!")
