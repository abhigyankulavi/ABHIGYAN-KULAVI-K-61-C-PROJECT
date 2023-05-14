# ABHIGYAN-KULAVI-K-61-C-PROJECT
 Bank Management System: Develop a program that simulates a bank management system, where customers can create an account, deposit and withdraw money, and view their balance.

Here are the variable descriptions for the Bank Management System code:
1.MAX_CUSTOMERS: a constant integer representing the maximum number of customers that can be stored in the system (set to 100 in this code)
2.struct Account: a user-defined structure representing a customer's account, with three members:
3.accountNumber: an integer representing the customer's account number
4.name: a character array representing the customer's name
5.balance: a float representing the current balance of the customer's account
6.customers: an array of struct Account representing the customers in the system
7.numCustomers: an integer representing the current number of customers in the system
8.createAccount(): a function that creates a new account for a customer and adds it to the customers array
9.deposit(): a function that allows a customer to deposit money into their account
10.withdraw(): a function that allows a customer to withdraw money from their account
11.viewBalance(): a function that allows a customer to view the current balance of their account
12.main(): the main function of the program, which displays a menu of options for the user to choose from and calls the appropriate functions based on their choice
13.choice: an integer representing the user's menu choice (set by user input in the main() function)
14.newCustomer: a temporary struct Account used to create a new customer account in the createAccount() function
15.accountNumber: an integer representing the account number entered by the user (used in the deposit(), withdraw(), and viewBalance() functions)
16.amount: a float representing the amount of money entered by the user for a deposit or withdrawal (used in the deposit() and withdraw() functions)
17.i: a loop counter used in the deposit(), withdraw(), and viewBalance() functions to search the customers array for a customer account with a matching account number

Here are the descriptions of the functions used in the Bank Management System code:

1.createAccount(): This function prompts the user for a new account number, name, and initial balance, creates a new struct Account with these values, and adds it to the customers array. It also increments the numCustomers variable to reflect the new customer added to the system.
2.deposit(): This function prompts the user for an account number and an amount to deposit. It searches the customers array for a customer account with a matching account number, and if found, it adds the deposit amount to the account's balance.
3.withdraw(): This function prompts the user for an account number and an amount to withdraw. It searches the customers array for a customer account with a matching account number, and if found, it checks that the account has sufficient balance to cover the withdrawal amount. If so, it subtracts the withdrawal amount from the account's balance.
4.viewBalance(): This function prompts the user for an account number and searches the customers array for a customer account with a matching account number. If found, it displays the account's current balance to the user.
5.main(): This is the main function of the program, which displays a menu of options for the user to choose from and calls the appropriate functions based on their choice. It runs in a loop until the user chooses to exit the program.

