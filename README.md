# Bank-of-Sanky
Bank of Sanky is a Mobile Banking android app for bank transaction.

Bank of Sanky app allows a customer to log in to his account, check his current checking and savings balance, deposit or withdraw money from both accounts and transfer funds from one account to another.

Customer must provide a valid username and password to log into his accounts. Upon successful login, the customer is redirected to the menu screen where he can choose to proceed to Checking Account, Savings Account or Transfer Funds screens. Checking and Savings screens enable the user to see his current checking or savings balance and deposit or withdraw money from his checking or savings account. Transfer screen enables the user to choose between transferring money from checking to a savings account or vice versa.

Each screen uses a java class to handle the programming logic. Java classes include all necessary conditions to check the validity of transactions. For example, the user can’t withdraw more money than it’s available in the account.

Bank of Sanky app keeps track of customer’s balance by utilizing Android Shared Preferences file. Each time the user makes a transaction, shared preferences file is updated. When the user quits the application and logs in again, his previous balances are retrieved from shared preferences file.

Bank of Sanky app security is implemented by requiring a customer to provide valid username and password. After three unsuccessful logins, the application shuts down.

Bank of Sanky app is created with Android Studio to run on all Android phones.

