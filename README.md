# Cafe-management-system
1.Swayam - Arrays for storing menu details and storing orders.

2.Jaya - Function to display menu and input choice from the customer.

3.Ishu - Function to take an order from the customer.

4.Ria - Function to generate bill.

5.Gaurav - Totalling of all items and calling all functions in main function.

Macro functions used are :- #define MAX_ITEMS 7, #define MAX_ORDERS 10

Arrays used are :- item_ids[MAX_ITEMS], item_names[MAX_ITEMS][30], item_prices[MAX_ITEMS], orderitem_ids[MAX_ORDERS], orderquantities[MAX_ORDERS] 

Functions used are :- displayMenu(), takeOrder(), generateBill(), main()

Loops used :- for, while 


output:



Welcome to the Cafe!
---- Cafe Menu ----
1. Coffee - 250
2. Tea - 100
3. Sandwich - 100
4. Cake - 300
5. Burger - 200
6. Salad - 100
7. Coke - 150
-------------------
Enter item ID to order (0 to finish): 1
Enter quantity for Coffee: 1
Enter item ID to order (0 to finish): 0
----- Order Bill -----
Coffee x 1 = 250.00
----------------------
Total: 250.00
Thank you for your order!
