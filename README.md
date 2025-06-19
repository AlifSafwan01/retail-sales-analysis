# Quantium Data Analytics Job Simulation - Data Preparation and Customer Analytics
In this project simulation, I was assigned to Quantium's Retail Analytics team. I was approached by our client, the Category Manager for Chips, who wants to better understand the types of customers who purchase chips and their purchasing behavior.

The objective of this project is as follows :-
1. Analyze transaction and customer data to identify trends and inconsistencies.
2. Develop metrics and examine sales drivers to gain insights into overall sales performance.
3. Create visualizations and prepare findings to formulate a clear recommendation for the client's strategy.

## Customers and Transactions Data
The data used in this projects is as follows :-
1. [Transaction Data](QVI_transaction_data.xlsx)

This dataset contains 8 variables and 264,836 observations :-

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

This dataset contains 3 variables and 72,637 observations :-

| Variable | Description |
| --- | --- |
| LYLTY_CARD_NBR | The unique ID for each customer |
| LIFESTAGE |  The customer's life stage category (7 groups) |
| PREMIUM_CUSTOMER | The customer's budget category (3 groups) |

## Chip Data

The Chip dataset is a cleaned and prepared version created by removing outlier, filtering out non-chip products, formatting dates, and extracting product brand, name and size from PROD_NAME. It also involved correcting inconsistencies and merging the Transaction and Customer data using LYLTY_CARD_NBR.

This dataset contains 13 variables and 251,158 observations :-

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
| packed_size | The size of the packaging (g) |
| product_brand | The chip brand |
| product_name | The chip product name |
| LIFESTAGE |  The customer's life stage category (7 groups) |
| PREMIUM_CUSTOMER | The customer's budget category (3 groups) |

## Analysis and Report

The full report is provided in three formats.
1. [Chip-Analysis.Rmd](Chip-Analysis.Rmd) - R markdown format.
2. [Chip-Analysis.html](Chip-Analysis.html) - HTML format.
3. [Chip-Analysis.pdf](Chip-Analysis.pdf) - PDF format.
