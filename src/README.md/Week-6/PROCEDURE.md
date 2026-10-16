## Restaurant Order, Kitchen & Billing System
## Week-6
## Objective

To develop a Java program for managing restaurant orders using 1-D and 2-D arrays along with methods and loops.

## Problem

The restaurant needs to store menu items and their prices, accept customer orders, calculate the bill, and display the kitchen status.

## Input
Customer name
Menu choice
Quantity
Kitchen status
## Process
1. Store menu item names and prices in 1-D arrays.
2. Store menu numbers and prices using a 2-D array.
3. Display the menu by traversing the arrays.
4. Read the customer's menu choice.
5. Use the choice as an array index to find the selected price.
6. Read the quantity.
7. Calculate the subtotal using a method.
8. Count the ordered items using recursion.
9. Calculate discount and tax.
10. Read the kitchen status.
11. Display the kitchen status and final bill.

## Output

The program displays:

Restaurant menu
Customer name
Total number of items
Kitchen status
Subtotal
Discount
Tax
Total bill
## Algorithm
• Start.
•Create arrays for menu items and prices.
•Create a 2-D array for menu details.
•Read the customer name.
•Set subtotal and itemCount to zero.
•Display menu items using a for loop.
•Read the menu choice.
•If the choice is 4, finish the order.
•If the choice is invalid, continue the loop.
•Calculate the array index as choice - 1.
•Get the price from the prices array.
•Read the quantity.
•Calculate the item subtotal.
•Add it to the total subtotal.
•Use recursion to count the items.
•Calculate discount, tax and total.
•Read the kitchen status.
•Display the final order details and bill.
•Stop.
## Concepts Used
1-D arrays
2-D arrays
Array indexing
length
Array traversal
Searching/accessing array elements
for loop
do-while loop
Methods
Recursion
if-else-if
switch
Accumulation