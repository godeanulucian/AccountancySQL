# AccountancySQL

Database Project -2
It is considered an online application that is used to create the accounting balance of a 
company. The application uses an Oracle database (considered as a collection of tables) for 
data storage, which must contain the information listed below:
- account number - maximum 5 digits,
- account description - maximum 50 characters,
- account type – 2 characters ('ca' - capital, 'pa' - passive, 'ac' - active),
- balance_initial (amount available in the account at the beginning of the current year),
- balance (the amount available in the account at the current moment),
- transaction number (cannot be greater than 10000),
- transaction date - calendar date,
- the amount transacted (for one account, in a single transaction, it cannot be higher than 
10,000),
- creditor account number - (the account from which the money goes) maximum 5 digits
- debit account number - (the account where the money goes) maximum 5 digits
- transaction description - maximum 10 characters.
Is required:
1. To design the database, writing the commands to create the tables and 
imposing all the constraints that are considered useful from a functional 
and data integrity point of view.
2. To write the commands to populate the tables with information (minimum 5 articles in each 
table).
3. To implement a stored procedure that implements a transaction, knowing that this requires 2 
accounts - one debtor (from which the money leaves) and one creditor (where the money 
enters). The procedure receives as input parameters the transaction number, the debtor 
account, the creditor account, the transacted amount as well as a description of the 
transaction.
4. To implement a trigger that, when a transaction is entered, automatically recalculates the 
balance of the accounts involved in the transaction
5. To create a report in which to display all the transactions in which a certain account is 
used.
6. To display all the transactions that were entered during the period (01.01.2020- 
01.06.2020)
7. To calculate and display the total creditor and debitor amount for all the accounts 
that were involved in the transactions
8. To display all transactions involving accounts of a certain type ('ca' - capital, 'pa' - 
passive, or 'ac' - active)
9. To delete an account if there are no transactions for it
10. To display the account that appears in the most transactions as well as the number of transactions 
in which it appears.
Translated from Romanian to English - www.onlinedoctranslator.com