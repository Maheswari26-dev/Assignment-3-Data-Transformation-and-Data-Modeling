Step 1 Keep only first 500 rows ( Home- Keep rows - keep top rows - enter 500 - ok
Change order data to date ( Find order date column - data type icon click - Date - repalce current
Change amount and target ( Select amount coloumn - fixed decimal number) Same for target
Fix location format ( Select location column - Transform - Replace values- to find , - repalce with , - ok
Amount to fixed decimal no ( Amount column  - top data type dropdown - select fixed decimal number 
Create profit margin ( click add column- custom coloumn - new column Profit margin - type [profit]/[amount] - ok
Profit status ( add column - conditional column - name profit status - profit, is less than, 0, loss - add clause - profit, is = to, 0, break even- ok
Check duplicates (Order details - home - remove rows - remove duplicates)
Grouping and aggregating ( Crete the duplicate - click order details 2 - select duplicate - rename to order id count) ( group ( SELECT ORDER ID - home - group by: order id column name order count operation count rows - ok
Average profit + toatal amount by sub category
Sales target - total target by month
Created relationships
Check the relatioships
