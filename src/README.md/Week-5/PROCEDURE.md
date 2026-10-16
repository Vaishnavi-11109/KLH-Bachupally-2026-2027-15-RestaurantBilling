## Restaurant Order, Kitchen & Billing System
## Week-5
## Objective

To develop a Java program for managing restaurant orders, calculating bills, and displaying kitchen status using methods and recursion.

## Problem

The restaurant needs a system to accept customer orders, calculate the subtotal, discount, tax and total bill, count items, and display the kitchen status.

## Input
Customer name
Menu choice
Quantity
Kitchen status
## Process
•Read the customer name.
•Display the restaurant menu.
•Accept the menu choice and quantity.
•Calculate the item subtotal using a method.
•Use recursion to count the ordered items.
•Calculate the discount using a method.
•Calculate the tax using a method.
•Calculate the final bill.
•Display the kitchen status using a method.
•Display the final bill.

## Output

The program displays:

Customer name
Total number of items
Kitchen status
Subtotal
Discount
Tax
Total bill

## Algorithm
1. Start.
2. Read customer name.
3. Initialize subtotal = 0 and itemCount = 0.
4. Display the menu using a do-while loop.
5. Read the user's choice.
6. If choice is 4, finish the order.
7. If the choice is invalid, continue to the next iteration.
8. Read the quantity.
9. Select the price using switch.
10. Call calculateSubtotal() and add the result to subtotal.
11. Call countItems() to count the items recursively.
12. Call calculateDiscount() to calculate discount.
13. Call calculateTax() to calculate tax.
14. Calculate the total bill.
15. Read the kitchen status.
16. Call displayKitchenStatus().
17. Display the bill.
18. Stop.

## Concepts Used
Static methods
Method parameters
Return values
void methods
Method decomposition
if-else-if
switch
do-while
break
continue
Recursion
Base case
Recursive case