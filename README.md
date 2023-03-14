This project uses data from a DVD rental database which contains information about the company's sales, inventory, staff and customers.
The business report created with the data sets provides a summary view of the company's sales per month, sorted by film category.

The purpose of the report is to answer the company's business question: How much revenue is the company receiving for each category, each month.

The data is extracted first into a Detailed Table for high-level overview of sales. 
From the Detailed Table, a Summary Table is created for the summarized view of category sales per month.

The trigger function updates the Summary table whenever new data is entered into the Detailed table.
The stored procedure is intended for refreshing the tables monthly with new data.
