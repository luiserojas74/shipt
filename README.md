# shipt
Shipt coding exercise

In order to run Flask, Python 2.7 and sqlite3 are needed. In a command line execute python shipt.py and the web server will go up.

On a browser, type for the URL: /api/v1/orders/categories?cust_id=[CustomerId] 
   and it will return a JSON format with products sold by category.
Type /api/v1/orders/products?idate=[InitialDate]&fdate=[FinalDate]&period=[Period]&type=[PeriodType] 
   and it will return a CSV file with products sold in that range of dates.
Type /api/v1/orders?cust_id=[CustomerId] and it will return a JSON format with products per customer.
