## Restaurant Order, Kitchen & Billing System
## Week-2 Procedure
## Objective

To develop a Java program that accepts customer and order details, calculates the subtotal, tax, and total bill using appropriate data types, and displays the order and bill details.

## Problem

A restaurant needs a simple system to store customer orders and calculate the final bill by adding a 5% tax to the order subtotal.

## Input
-Customer name
-Food item
-Quantity
-Price per item
## Process
1. Read customer and order details using Scanner.
2. Store the customer name and food item as String.
3. Store quantity as int.
4. Store price as double.
5. Calculate the subtotal.
6. Calculate 5% tax.
7. Add the tax to the subtotal to get the total bill.
8. Display the order and kitchen status.
9. Display the subtotal, tax, and total using formatted output.
## Output
Customer name
Food item
Quantity
Price per item
Kitchen order status
Subtotal
5% tax
Total bill
## Algorithm
• Start.
• Create a Scanner object.
• Declare the currency constant.
• Read customer name.
• Read food item.
• Read quantity.
• Read price per item.
• Calculate subtotal = quantity × price.
• Calculate tax = subtotal × 0.05.
• Calculate total = subtotal + tax.
• Display order details.
• Display kitchen status.
• Display subtotal, tax, and total bill using printf.
• Close the Scanner.
• Stop.
## Concepts Used
Variables
String
int
double
Constants using final
Literals
Arithmetic operators
Expressions
Scanner
nextLine()
nextInt()
nextDouble()
Formatted output using printf
Floating-point calculations