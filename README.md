# Analyzing Amazon Sales data

## About Dataset:
The "Amazon Sales Data" dataset is a comprehensive collection of 14 columns in CSV file. This dataset provides valuable insights into the ordering patterns, product details, quantities, prices, order dates, and purchase revenue associated with Amazon orders.

The dataset contains the following columns:

* Region : Name of the region where product ordered.
* Country : Name of country where product ordered.
* Item Type : Type of item ordered.       
* Sales Channel : Is product ordered online or offline.  
* Order Priority : Priority of the order.
* Order Date : The date when the order was placed.
* Order ID : Unique identification number for each order.
* Ship Date : The date when the order was shipped.
* Units Sold : Number of product sold.
* Unit Price : The price of each product unit. (amount of money a customer pays for product)
* Unit Cost : Cost of the product. (amount of money it takes to produce product)
* Total Revenue : The total income a business receives from selling a good or service. Also known as sales.
* Total Cost : The total expenses incurred in producing a good or service.
* Total Profit : The amount of money remaining after all costs, expenses, and taxes have been deducted from the revenue.
  
By analyzing this dataset, users can gain a deep understanding of Amazon sales trends over the course of 12 months. It provides a valuable resource for market research, sales forecasting, product analysis, and customer behavior analysis. Researchers, data scientists, and business professionals can leverage this dataset to uncover patterns, identify popular products, understand pricing strategies, and derive actionable insights for optimizing sales and business strategies.

### Problem Statement:

* Sales management has gained importance to meet increasing competition and the need for improved methods of distribution to reduce cost and to increase profits. Sales management today is the most important function in a commercial and business enterprise.
* Do ETL: Extract-Transform-Load some Amazon dataset and find for me Sales-trend -> month-wise, year-wise, yearly_month-wise Find key metrics and factors and show the meaningful relationships between attributes. Do your own research and come up with your findings.

### Approach
The main goal of the project is to find key metrics and factors and then show meaningful relationships between them based on different features available in the dataset.

Data Collection : Imported data from various datasets available in the project using Pandas library.

Data Cleaning : Removed missing values and created new features as per insights.

Data Preprocessing : Modified the structure of data in order to make it more understandable and suitable and convenient for statistical analysis.

Data Analysis : I started analyzing dataset using Pandas,Numpy,Matplotlib and Seaborn.

Data Visualization : Plotted graphs to get insights about dependent and independent variables.

Also to solve the problem, three new fields were created from order data, such as
* Year: Year when the product was ordered.
* Month: Month when the product was ordered.
* Year_month: year and month when the product ordered.
