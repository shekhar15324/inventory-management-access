📦 Inventory Management System (MS Access)
This project is a simple Inventory Management System built using Microsoft Access, designed to help businesses track products, manage supplier information, and monitor purchases efficiently.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🔧 Features
✅ Relational Database Design: Built with 3 connected tables — Products, Suppliers, and Purchases.

📌 Data Integrity: Enforced with primary/foreign keys, lookup fields, and validation rules.

📋 User-Friendly Forms: 3 custom forms for managing Products, Suppliers, and Purchases.

📊 Reports: Auto-generated reports summarizing:

Monthly purchase records

Supplier performance

Stock status and valuation

📈 SQL Queries: Includes over 7 queries for low-stock alerts, inventory value calculation, etc.

⚙️ VBA Macro: Custom button to auto-calculate Total Price in Purchases using Quantity × Price.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📁 Database Structure

1. Suppliers

| Field        | Description              |
| ------------ | ------------------------ |
| SupplierID   | Primary Key (AutoNumber) |
| SupplierName | Supplier Name (Text)     |
| Email        | Supplier Email (Text)    |
| Phone        | Contact Number (Text)    |




2. Products

| Field         | Description                             |
| ------------- | --------------------------------------- |
| ProductID     | Primary Key (AutoNumber)                |
| ProductName   | Name of the Product (Text)              |
| Category      | Product Category (Text)                 |
| StockQuantity | Number of units available (Number)      |
| SupplierID    | Foreign Key (Lookup to Suppliers)       |
| Price         | Unit price of product (Currency/Number) |


3. Purchases

| Field        | Description                                  |
| ------------ | -------------------------------------------- |
| PurchaseID   | Primary Key (AutoNumber)                     |
| ProductID    | Foreign Key (Lookup to Products)             |
| Quantity     | Quantity purchased (Number)                  |
| TotalPrice   | Auto-calculated via VBA (`Quantity × Price`) |
| PurchaseDate | Date of Purchase (Date/Time)                 |

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

📂 Sample Data Files
You can find sample .csv data in the /data folder:

suppliers.csv

products.csv

purchases.csv
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🛠 Technologies Used
Microsoft Access 365

SQL

VBA (for automation)

Excel/CSV for data import/export
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📌 How to Use
Clone or download this repository.

-> Open the .accdb file in Microsoft Access.

-> Import sample .csv files using External Data > Import Text File.

Explore:

-> Forms for data entry

-> Queries for insights

-> Reports for summaries
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🙏 Acknowledgments
Thanks to all mentors and peers who helped guide me through this project 🙌
Special appreciation to the OpenAI community for guidance on best practices and structure.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🔗 Author
Shekhar Kotipalli
Aspiring Data Analyst | SQL & BI Enthusiast




