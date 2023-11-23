# Coffee Sales Dashboard - MS Excel
This project was inspired by the guidance and dataset provided by Mo Chen from the YouTube channel [Data with Mo](https://www.youtube.com/@datawithmo). The primary objective was to transform a complex dataset that provides customer, product and order data into an engaging dashboard using Excel functionalities.

## Project Highlights

📂 Data Transformation:
- Leveraged XLOOKUP() to populate the "orders" worksheet with customer data.
- Utilized INDEX() MATCH() to pull in product information into the "orders" worksheet.
- Calculated sales figures.
- Employed IF() functions to replace abbreviations of the "Coffee Type" and "Roast Type" columns.

📅 Data Formatting:
- Formatted the order date to ensure a consistent date format.
- Customized the "Size" column to display "KG" after each value.
- Formatted the "Unit Price" and "Sales" columns as currency.

🗂 Data Management:
- Removed duplicate entries to maintain data integrity.
- Created a table named "orders_table" for easy data referencing.

📊 Data Analysis:
- Generated pivot tables to visualize sales of each coffee type over time. Added line chart for dynamic visualization.
- Examined gross sales by country using another pivot table and bar chart.
- Identified top customers with a pivot table and showcased the results through column chart.

📈 Dashboard Creation:
- Designed a sleek "Dashboard" worksheet, hiding gridlines for a clean look.
- Incorporated a timeline for efficient date-based filtering.
- Added slicers for size, roast type, and loyalty card status for easy data filtration.
- Meticulously formatted all elements, ensuring a polished final dashboard.
