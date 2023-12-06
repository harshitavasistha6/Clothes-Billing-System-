# Clothes-Billing-System-
This Python code is for a clothing billing system application with a graphical user interface made using Tkinter.

It has the following key components:

1. Customer Details Frame: To capture customer name, phone number and bill number. Allows searching past bills by number.

2. Product Frames: Captures quantity of various clothing items under categories like Men's Wear, Women's Wear, Kids' Wear.

3. Billing Area: Displays the generated bill with all itemized listings, quantity, rates and tax amounts.

4. Bill Menu Frame: Shows subtotals per clothing category, tax amounts per category and total bill amount.

5. Button Frame: Has options to generate total, generate bill, print bill, email bill etc.

Some key functions:

- bill(): Generates the itemized bill content in the billing area text widget
- total(): Calculates all category subtotals, taxes and grand total
- print_bill(): Prints the bill content to a temp text file and opens it for printing 
- savebill(): Saves the generated bill with a random bill number for future reference

Overall, it provides a complete end-to-end order and billing functionality for a multi-category clothing store with reasonable taxation built in.


  
