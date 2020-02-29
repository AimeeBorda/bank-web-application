Now, we need to provide a way for clients to create a transaction i.e., move money between accounts or to someone else's account. 

Make sure you address error cases like
* client does not have enough money in the account to do a transaction
* client is being cheeky and try to transfer a negative amount to request money from someone else's account
* target account does not exist
* and others.