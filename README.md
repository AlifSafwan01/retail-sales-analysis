# Quantium Data Analytics Job Simulation - Data Preparation and Customer Analytics
In this project simulation, I assigned as a part of Quantium's Retail Analytics team and have been approached by our client, the Category Manager for Chips, who want to better understand the types of customers who purchase chips and their purchasing behavior.

The objective of this project is stated as below :-
1. Analyze transaction and customer data to identify trends and inconsistencies.
2. Develop metrics and examine sales drivers to gain insights into overall sales performance.
3. Create visualizations and prepare findings to formulate a clear recommendation for the client's strategy.

## Customers and Transactions Data
The data used in this projects as below :-
1. [Transaction Data](QVI_transaction_data.xlsx)

In this data contains 8 variables and 264,836 observations :-

| Variable | Description |
| --- | --- |
| DATE | The date of transaction occured|
| STORE_NBR | The unique ID assigned to each store |
| LYLTY_CARD_NBR | The unique ID for each customer |
| TXN_ID | The unique ID for each transaction |
| PROD_NBR | The unique ID for each chip product |
| PROD_NAME | The unfiltered name of chip product |
| PROD_QTY | The quantity purchased by the customer per transaction |
| TOT_SALES | The total price per transaction |
2. [Customer Data](QVI_purchase_behaviour.csv)

In this data contains 3 variables and 72,637 observations :-

| Variable | Description |
| --- | --- |
| LYLTY_CARD_NBR | The unique ID for each customer |
| LIFESTAGE |  The category of customer life stage (7 groups) |
| PREMIUM_CUSTOMER | The category of customer shopping budget (3 groups) |

## Chip Data

Chip data is prepared data after removing outlier, removing non chip product, formatting date, extracting product brand, name and size from PROD_NAME, removing inconsitency and joining Transaction and Customer data through LYLTY_CARD_NBR.

In this data contains 13 variables and 251,158 observations :-

| Variable | Description |
| --- | --- |
| DATE | The date of transaction occured|
| STORE_NBR | The unique ID assigned to each store |
| LYLTY_CARD_NBR | The unique ID for each customer |
| TXN_ID | The unique ID for each transaction |
| PROD_NBR | The unique ID for each chip product |
| PROD_NAME | The unfiltered name of chip product |
| PROD_QTY | The quantity purchased by the customer per transaction |
| TOT_SALES | The total price per transaction |
| packed_size | The size of packaging (g) |
| product_brand | The brand of chip |
| product_name | The name of chip |
| LIFESTAGE |  The category of customer life stage (7 groups) |
| PREMIUM_CUSTOMER | The category of customer shopping budget (3 groups) |

## Analysis and Report

For full report, 
