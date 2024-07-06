# Sales Performance Analysis

This project performs a comprehensive analysis of sales data to identify trends, seasonal patterns, and top-performing products. It also includes a predictive model for sales forecasting. The project utilizes Apache Spark for data processing and analysis, and Matplotlib for visualizations.

## Dataset

The dataset used in this project is named `auto_sales_data.csv` and contains the following columns:

- ORDERNUMBER
- QUANTITYORDERED
- PRICEEACH
- ORDERLINENUMBER
- SALES
- ORDERDATE
- DAYS_SINCE_LASTORDER
- STATUS
- PRODUCTLINE
- MSRP
- PRODUCTCODE
- CUSTOMERNAME
- PHONE
- ADDRESSLINE1
- CITY
- POSTALCODE
- COUNTRY
- CONTACTLASTNAME
- CONTACTFIRSTNAME
- DEALSIZE

## Prerequisites

Before running the code, ensure you have the following installed:

- Python 3.6 or higher
- Apache Spark
- Pandas
- Matplotlib

You can install the required Python libraries using pip:

```bash
pip install pandas matplotlib pyspark
