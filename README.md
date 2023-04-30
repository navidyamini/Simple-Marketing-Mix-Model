# Simple-Marketing-Mix-Model

## Data Description:



To better clarify this. We have three different tables: 

- **daily_transactions: 
Here you can find the individual transactions per day. 
- **daily_spend_by_channel:
For the same dates as before, you can find the daily spend by channel in €
- **daily_operations: 
Keeping the date range, here is some extra info of the products. For instance: if they belong to an updated website or not, or if all the products are fully available on a specific date.

| Field name                   | Description          
| ---------------------------- | ------------------------------------ 
| date                         | Uhm, date          
| #channel#_spend              | Uhm, spend by channel in €
| transaction_id               | ID for each transaction
| stock_availability_perc      | Number of available items in %
| website_version              | Version of the website (old or new)

