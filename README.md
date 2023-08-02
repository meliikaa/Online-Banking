# Online-Banking
This assignment involves implementing an online banking system using Python. The system allows users to sign up, log in, change their password, delete their account, update their bank account balance, and transfer money to other users' bank accounts. The implementation involves working with file I/O and dictionaries.

**Files**

The assignment requires importing data from two files: "users.txt" and "bank.txt". The "users.txt" file contains user information, while the "bank.txt" file contains account information. Make sure to review the content of these files before proceeding with the implementation.

**Functions**

The assignment provides function definitions for each task. Your task is to write the code for these functions based on the provided instructions and hints. The functions include:

-<u>import_and_create_users(filename)</u>: This function reads the "users.txt" file and creates a user accounts dictionary and a login dictionary. Each line in the file should be in the format "username - password". The user accounts dictionary stores the username as the key and the password as the value. The login dictionary stores the username as the key and the login status (True/False) as the value.

-<u>import_and_create_accounts(filename)</u> This function reads the "bank.txt" file and creates a bank accounts dictionary. Each line in the file should be in the format "username - balance". The bank accounts dictionary stores the username as the key and the account balance as the value.

-<u>signup(user_accounts, log_in, username, password)</u>: This function allows users to sign up with the system. It checks the validity of the username and password based on certain requirements and updates the user_accounts and log_in dictionaries accordingly.

-<u>login(log_in, username, password)</u>: This function allows users to log in to the system. It verifies the username and password against the user_accounts dictionary and updates the login status in the log_in dictionary.

-<u>change_password(user_accounts, log_in, username, current_password, new_password)</u>: This function allows users to change their password. It verifies the username, current password, and new password against the user_accounts dictionary and updates the password if the verification is successful.

-<u>delete_account(user_accounts, log_in, bank_accounts, username)</u>: This function allows users to delete their account. It removes the user's information from the user_accounts, log_in, and bank_accounts dictionaries.

-<u>update(bank_accounts, log_in, username, amount)</u>: This function updates a user's bank account balance. It verifies the user's login status, checks if the user exists in the bank_accounts dictionary, and ensures that the updated balance does not become negative.

-<u>transfer(bank_accounts, log_in, sender, receiver, amount)</u>: This function transfers money from one user's bank account to another user's bank account. It verifies the login status of both the sender and receiver, checks if they exist in the bank_accounts dictionary, and ensures that the sender has sufficient balance to perform the transfer.

**Instructions**

Read the docstrings provided for each function to understand the requirements and hints for writing the code. Implement the code for each function accordingly. You may need to use additional functions or methods to achieve the desired functionality.

Make sure to test your implementation using the provided assertion tests. These tests verify if your functions produce the expected results. If all the tests pass, it means your implementation is correct.

Attribution
This assignment is presented by UPENN on Coursera.

Please refer to the provided code and instructions for further details on the implementation of each function.
