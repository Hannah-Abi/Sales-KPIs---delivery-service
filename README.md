## Task goals 
- Calculation of profitability KPIs metrics 
- Guiding decision making by giving users of the data visibility into profitability of certain purchases, venues, and items
## Introduction and Data 
The data consists of three csv ﬁles:
### 1.	purchase_data.csv
The data will get you information about the purchase itself.
- PURCHASE_ID: The unique identiﬁer of the purchase
- TIME_RECEIVED: The time when the customer made the order.
- TIME_DELIVERED: The time when the order was delivered to the customer.
- CURRENCY: Local currency the purchase was made in
- COUNTRY: The country of the venue where the purchase was made
- VENUE_ID: The unique identiﬁer of the venue 
### 2.	purchase_item_data.csv
You can find exactly which items were purchased. 
- PRODUCT_ID: Identiﬁer for the item used. 
- PURCHASE_ID: The unique identiﬁer of the purchase
- COUNT: How many items of a certain type were purchased
- VENUE_ID: The unique identiﬁer of the venue
- BASEPRICE: The price of an item in local currency including value-added tax (VAT)
- VAT_PERCENTAGE: Value-added tax (VAT) percentage
### 3.	item_data.csv
The data has item-level information including costs for the items that the company pays for the vendors.
- VENUE_ID: The unique identiﬁer of the venue
- TIMESTAMP: Time when the item became available
- BRAND: Name of the brand of a product
- MANUFACTURER: Name of the manufacturer of a product
- COST_PER_UNIT: Cost of single unit of item in local currency excluding value-added tax (VAT)
- COST_PER_UNIT_EUR: Cost of single unit of item in Euro excluding value-added tax (VAT)
- CURRENCY: Currency for the item price
- APPLICABLE_TAX_PERC: Applicable tax percentage of the item
- PRODUCT_ID: Identiﬁer for the item used. 
- ITEM_IDENTIFIER: Global Trade Item Number (GTIN)
- EXTERNAL_ID: External ID of the item used by the eternal vendors. 
## Tasks
### Task 0 – Exploratory Data Analysis 
- What assumptions about the data did you make when creating your gross margin calculations?
- Did you encounter any problems with the data? And if you did, how did you solve them?
- Which additional data sources or business information do you think could be used to improve your solution?
### Task 1
Using SQL, create a query that produces a table where we can see the proﬁtability of each purchase. Think about what granularity is best for this, which ﬁelds should be included, and how the solution works so that it can also handle any small errors there might be in the dataset and if any further data would be introduced.
### Task 2
- Calculate and visualize the following KPIs:
	- Top 10 venues with the highest margins, and plot the relationship between the margin and average order size.
	- Top 5 countries for each of the following metrics:
	- average order size
	- average order value
	- order volume
- Plot the monthly cumulative Woltwide (i.e. global) margin



	 

	 

