# BubbleTeaApp (An interactive console-based app that lets you store and change customer data for various branches)

This is application deals with customer data (names, phone numbers, and transactions) for branches like Sharetea - a popular 
franchise that sells bubble tea.

The app contains the following:
- a Sharetea class with an ArrayList of branches.
- a Branch class with a branch name and an ArrayList of customers.
- a Customer class with name, number, and an ArrayList (of doubles) to represent their transactions.

Customer class includes:
- constructor(s)
- getters
- setters

Branch class does the following:
- checks if a phone number already exists
- adds customers - validates the data to make sure we're not adding customers if the phone number already exists.
- adds transactions on a customer
- validates input to make sure it's a valid number
- removes a customer
- edits a customer name
- removes a transaction
- edits a transaction
- retrieves names of all customers
- retrieves all transactions for a given customer

Sharetea class does the following:
- adds branches
- edits branch
- removes branch
- retrieves names of all branches
