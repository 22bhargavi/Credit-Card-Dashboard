📊 Credit Card and Customer Data Management Project
Overview 📝
This project sets up a SQL database to manage both credit card data and customer details efficiently. Using structured tables, it imports data from CSV files and allows you to expand the database with additional data entries. The project is designed to ensure smooth handling of real-world data, including managing errors during imports and maintaining data consistency.

Key Features ⚙️
Database Creation: We begin by creating a dedicated credit card database called ccdb.
Data Tables:
The cc_detail table captures key credit card details like card type, annual fees, transaction amounts, and utilization.
The cust_detail table stores essential customer information, such as demographics, income, and satisfaction scores.
CSV Data Import: Use the COPY command to import customer and card data from CSV files, ensuring a seamless process of filling up the database.
Error Handling: We include mechanisms to handle date format errors, ensuring proper date formats for accurate imports.
How to Use 🔧
Set up the Database: Run the SQL commands to create the ccdb database and the two tables: cc_detail and cust_detail.
Import Data: Use the provided COPY commands to load data from CSV files into the respective tables. Ensure your CSV files are properly formatted.
Manage Errors: Handle potential date formatting issues by explicitly setting the PostgreSQL date style using SET datestyle TO 'ISO, DMY';.
Data Structure 🗂️
cc_detail Table:
Stores credit card information such as:
Client number, card category, annual fees
Transaction details and utilization ratio
cust_detail Table:
Contains customer information like:
Age, gender, marital status, income
Satisfaction scores and dependent details
Additional Features 🚀
Expandable: You can easily import additional data (like week-53 data) into the existing tables by following the same process for the COPY command.
Error-proofing: We handle common errors such as incorrect date formats, ensuring smoother data imports.
Conclusion 💡
This project provides a solid foundation for managing credit card and customer data in SQL. It is perfect for anyone looking to handle large datasets, clean imports, and maintain data integrity with ease.
