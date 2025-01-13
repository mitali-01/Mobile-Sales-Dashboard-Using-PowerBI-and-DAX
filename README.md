# Power BI Mobile Sales Dashboard

This Power BI dashboard visualizes a mobile sales dataset, showcasing various insights into total sales, customer ratings, and mobile models. The dataset includes information about sales transactions, including transaction ID, product details, customer information, and payment methods.

## Columns and Measures

### Columns:
- **Date**: A column created from combining the `Day`, `Month`, and `Year` columns to form a `Date` column.
- **TotalAmt**: A column calculated as `Units Sold * Price Per Unit` to calculate the total amount for each sale.

### Measures:
- **DistinctCustomers**: A measure to count the distinct number of customers.
- **Total Sales**: A measure calculating the total sales amount across the dataset.
- **Total Units Sold**: A measure calculating the total number of units sold.

## Visualizations

### 1. **Map**: 
   - A map showing sales across different cities in the country.

### 2. **Tree Map**: 
   - A tree map to display the phones sold by different brands and mobile models, allowing users to quickly identify the best-sellers.

### 3. **Table**:
   - A table showing the top-selling products with their model, brand, total units sold, and total sales.

### 4. **Line Chart**:
   - A line chart displaying the trend of total sales and average customer ratings over time (quarterly).

### 5. **Pie Chart**:
   - A pie chart visualizing the sales distribution across different payment methods.

## Getting Started

To run this project locally, you need to have Power BI Desktop installed on your computer.

1. **Clone the repository**:
   - Clone this repository to your local machine to start working on the Power BI dashboard.
   
2. **Download the Dataset**:
   - Ensure you have the mobile sales dataset that is used for the visualizations. You can also download the dataset from here: https://github.com/SatishDhawale/Power_BI_Dashboard/blob/main/Mobile%20Sales%20Data.xlsx
   
3. **Open a `.pbix` file**:
   - Open a Power BI file in Power BI Desktop to start creating the dashboard.

## Installation

- **Power BI Desktop**: Download and install from the [official Power BI website](https://powerbi.microsoft.com/desktop/).

## Future Enhancements
- **Additional Visualizations**: Add more charts to display other metrics like customer demographics or more detailed analysis of product performance.
- **Interactivity**: Implement slicers or filters to allow users to drill down into specific regions or time periods.

## Acknowledgments
- This project uses a sample mobile sales dataset to showcase various Power BI features.
