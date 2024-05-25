# inventory_management

# Shoe inventory control Data Analysis

## Overview

This project involves analyzing historic stock/inventory data for a shoe selling company. The data includes information on the size of the shoes sold, product ID, date of sale, sale price, unit price, gender, and country. The goal of this project is to analyze the data and determine, with a 95% confidence interval, how much stock of each item a retailer should hold in the future.

## Libraries Used

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **matplotlib.pyplot**: For creating static, interactive, and animated visualizations.
- **datetime**: For manipulating dates and times.
- **seaborn**: For statistical data visualization.
- **geopy.geocoders**: For geocoding (converting addresses into latitude and longitude).
- **scipy**: For scientific and technical computing, including statistical functions.

## Analysis and Visualization

The following charts were plotted using Matplotlib and Seaborn to visualize the data:

1. **Box Plot of Mean Sale Price by Country and Size**: This chart shows the distribution of the mean sale price across different countries and shoe sizes.
2. **Country-wise Histogram for Size-wise Units Sold**: This histogram illustrates the distribution of units sold for each shoe size in different countries.
3. **Female, Germany, 2015 Sales Heatmap for Each Size**: This heatmap visualizes the sales data for females in Germany in 2015 for each shoe size.
4. **Male, US, 2016 Sales Heatmap for Each Size**: This heatmap visualizes the sales data for males in the US in 2016 for each shoe size.
5. **Line Chart for Total Sales by Year and Quarter**: This line chart shows the total sales over time, broken down by year and quarter.
6. **Line Chart for Year-wise Total Sales**: This line chart displays the total sales for each year.

## Statistical Analysis

The t-statistic was used to provide the 95% confidence interval for the stock quantities. This analysis helps determine the appropriate stock levels to maintain in the future based on historical sales data.

## Usage

To run the analysis, ensure you have the required libraries installed. You can install the necessary packages using the following command:

```bash
pip install pandas numpy matplotlib seaborn geopy scipy
```

Then, execute the Python script to perform the analysis and generate the visualizations.

## Conclusion

This project provides a comprehensive analysis of historic shoe sales data. By understanding past sales trends and calculating confidence intervals, retailers can make informed decisions about future stock levels to better meet customer demand.

## License

This project is licensed under the MIT License. 

## Additional

There are two good SQL questions applied every day in inventory management for additional exposure to application of SQL to inventory management.

---
