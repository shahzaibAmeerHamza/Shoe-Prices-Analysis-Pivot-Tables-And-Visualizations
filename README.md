**Shoe Prices Data Analysis**

**Overview**
This project analyzes shoe prices from various brands and sizes using Excel's pivot tables and visualization tools. The dataset contains information on shoe brands, sizes, and their respective prices (more than 5000 rows). Key goals include identifying price trends by brand and analyzing price distribution with respect to shoe sizes.

**Dataset**
The dataset includes the following main columns:

Brand: Shoe brand (e.g., Nike, Adidas, Puma).
Size: Shoe size.
Price: Price of the shoe.
color
offer price
(Dataset source is Kaggle)

**Project Goals**
Summarize shoe prices by brand and size using pivot tables.

**Visualize:**
Price trends for each brand using a line chart.
Price distribution by size using a pie chart.

Steps to Reproduce
Load Dataset:

Open the provided dataset Shoe_Prices.xlsx in Excel.
Create Pivot Table for Price Trends by Brand:

Drag Brand to Rows.
Drag Price to Values and set it to "Sum."
Add a slicer for Size to filter dynamically.
Create a line chart from this pivot table to show price trends by brand.
Create Pivot Table for Price Distribution by Size:

Drag Size to Rows.
Drag Price to Values and set it to "Sum."
Add a slicer for Brand to filter dynamically.
Create a pie chart from this pivot table to show price distribution by size.
Format Visualizations:

Add data labels and titles for better clarity.
Use consistent formatting and colors across all charts.
Results

**Line Chart:**
Showcases the sum of shoe prices for each brand.
Includes filters for different shoe sizes.

**Pie Chart:**
Displays the distribution of shoe prices with respect to sizes.
Includes filters for different brands.
Project Files

Shoe_Prices_Analysis.xlsx: Excel workbook containing the dataset, pivot tables, and visualizations.

**README.md:** Documentation for the project.

**Tools Used**
Microsoft Excel: For data analysis and visualization.
Pivot Tables & Charts: To summarize and visualize data.

**Insights**
Price Trends:
Certain brands dominate in terms of price accumulation.
Prices vary significantly across sizes for some brands.
Distribution by Size:

Larger sizes often correlate with higher overall prices.

**Future Work**
Extend analysis to include more columns, such as ratings or sales.
Integrate data with Power BI for interactive dashboards.

**License**
This project is licensed under the MIT License. You are free to use and modify it for personal or educational purposes.
