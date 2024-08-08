# -PISCINE-SEAFOOD-ANALYTICS-PROJECT

Piscine is a seller of fresh seafood. Each Sunday evening, the purchasing manager of Piscine purchases fresh seafood directly from the fishermen who catch the seafood. There are multiple types of seafood that Piscine sells in three quality grades. 'A' represents the highest quality and most expensive seafood, while 'C' represents the lowest quality. After purchasing seafood on Sunday evening, Piscine sells this seafood throughout the following week (Monday through Sunday) at its storefront in the city. 
Piscine employs a pricing model that applies a set profit margin to each product. That is, it increments the purchase price according to a set profit margin to determine the sale price.

We have Piscine's purchases and sales data for a month. 
The data is stored in an Excel spreadsheet that has three sheets: Purchases, Sales, and Margin: 

# -Purchases Sheet 
Purchase Date: The day seafood was purchased. Seafood is always purchased on Sunday evenings.  

PurchaseBatch: A unique ID for a weekly batch

Seller. The seller of the seafood. 

Type: Type of seafood. 

Quality. A (high), B (medium), or C (low). 

PurchasePrice: The price per pound for the batch. 

Quantity: Pounds of seafood in the batch. 

Item Number. A unique ID number for a type and grade. 

# -Sales Sheet 
SaleDate: Date of sale.

PurchaseBatch: Same as PurchaseBatch from Purchases sheet. 

SaleQuantity. Pounds of seafood sold. 


# -Margin Sheet 
ItemNumber. Same as Purchases sheet. 

Type: Same as Purchases sheet. 

Quality. Same as Purchases sheet. 

SetProfitMargin: The profit margin that the business applies to a specific seafood type and quality 
grade. 
