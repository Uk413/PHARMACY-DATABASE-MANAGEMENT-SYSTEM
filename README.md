:warning: **Please change host, user, and passowrd in pharmacy.py file as per your system credentials before running**
# Pharmacy Database Management System Using Python and MySQL

This project is database management system for a pharmacy. It is made with MySQL And Python connectivity.  It is a choice based program i.e., the program will perform the associated functions with the choice a user chooses. The functions performed by this program are
- Create medicines table
- Create customer table
- Insert medicines/products
- Show all medicines
- Show medicine from code
- Show medicine from name
- Show all customers
- Update price of a medicine
- Delete medicine
- Update stock
- Sell medicines(with generated bill)

# How to use?
1. Download the pharmacy.py file.
2. Navigate to the download folder.
3. Run cmd Terminal on the location.
4. type

            python pharmacy.py

5. Run the program and use.

## Functions used

### PYTHON
- **mysql.connector** – for connecting MySQL and Python
- **medic=mysql.connector.connect(host="localhost",user="root",password="1234")** – to connect MySQL and Python
- **mycursor=medic.cursor()** - to create a cursor
- **mycursor.execute()** - Execute commands in MySQL through Python By writing MySQL commands in the brackets in string format 
- **fetchall()** - fetches all the rows of a query result. It returns all the rows as a list of tuples. An empty list is returned if there is no record to fetch. cursor.
- **commit()** -This method sends a commit statement to the MySQL server, committing the current transaction. Since by default Connector/Python does not autocommit, it is important to call this method after every transaction that modifies data for tables that use transactional storage engines.

### MySQL
- **create database** - to create database
- **create table** - to create the table
- **use** - to use the database to make changes in the tables
- **insert into[tablename]values()** - to insert records in the table
- **delete** - to delete a record from a table
- **update** -to update record in the table
