Create a small web application for a retail bank using the framework of your choice.  The application should contain the following tables:
* **Profiles:** User ID (key), Password, Full name
* **Accounts:** Account ID (key), Account number, User ID, Current balance
* **Transactions:** Source account ID, Target account ID, Amount, Date and time

Employees of the bank should be able to do the following:
1. Create new clients.
2. Create new accounts for existing clients.

Clients of the bank should be able to do the following:
1. Log onto the application
  * Hint: This functionality is more challenging than it looks. If you are having trouble, consider listing clickable profiles on the client welcome page for a start. You can come back to this question after finishing tasks (2), (3) and (4) below.
2. Display the balance of all their accounts
3. List the transactions for each account over the past month / quarter / year
  * Hint: You can use a dropdown list to let users select the period for which they want to list transactions.
4. Transfer money between their accounts or to someone else’s account
  * Hint: Users can only perform a single transaction at a time, but make sure you address error cases.
5. Update their profile including their password (bonus)

Create 2-3 test profiles (each with a couple of accounts) to showcase the web application.