# ETG-Internship-Inventory-Management-System
**Creator:** K RUSHIKESH REDDY

## Problem:
One of the major issue for small scale shopkeepers is to keep track of their inventory and sales. Most oftenly they spend a lot of time and efforts to manage their inventory as well as keep record of their sales. 

## Introduction:
I have created an Inventory Management System to manage the goods for a small scale shops using the power of python and json.
This will save a lot of time and efforts of the shopkeepers and facillitate them in the tedious task of managing inventory and sales.
The project is a inventory management system. I have divided it in four parts.

The First part contains a nested dictionary of 50 products with product id as the key and other details like product name, price, expiry date, quantity and category as value of each key.Then the dictionary is converted to json file.

The Second part contain code to display only the product id and the product name is a neat way to the user.

Third Part involves the code to prompt the for the product id against which the product name and price is displayed, then user is asked to enter the quantity of product he wants to purchase. It goes on in a loop until user types in done. In each iteration, confirmation message is displayed to the user. Finally after user enters done, total bill is displayed. User is asked if he wants to print a bill. If he types in yes, a well presented bill is displayed with the product name, discounted price, normal price, category. I formatted it in a table format using f strings.

Fourth Part: whatever user purchases is modified in the copy of main dictionary and the sales.json is created.

## Functionalities and working:
This project is actually divided into 2 files:

**1.Adding_Elements_into_Inventory:**
In this part, We create a records.json file which contains all the Inventories with details like product id(barcode),name,quantity,price,isAvailable,Expiry date.
Here we can add new goods in the inventory and the records will be stored in records.json file.

**2.Product Purchase:**
In this part, a)We enter the transaction or purchase details like product id,no. of items purchased,name of customer, mobile number of customer.
b)If the purchased items are available in inventory, then Bill is generated
c)The detailes of the transactions are then stored in sales.json file with attributes like total transactions,transactio id,date,time, product name,total amount of purchase, customer name and customer mobile number.   

## Tools used:
1. python - 3.7
2. json

Thank You!
