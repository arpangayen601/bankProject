# bankProject
The code represents a basic banking system application where users can perform various banking operations. It includes the following classes and functionalities:
`CentralBank` class: This class represents a generic bank account and contains methods to create an account, display account details, search for an account by account number, deposit funds, withdraw funds, and remove an account.
`unb`, `nbd`, and `fgb` classes: These classes are subclasses of `CentralBank` and represent different types of bank accounts (e.g., UNB, NBD, FGB) with varying minimum balance requirements.
`BankDriver` class: This class serves as the main driver class for the banking application. It allows users to interact with the system through a menu-driven console interface.

*****The main functionalities of the application are as follows*****

Account Creation: Users can create a new bank account by providing their name, account number, account type, and initial balance. The account type determines which subclass of `CentralBank` to use for the new account.
Display Account Details: Users can view the details of all existing accounts, such as account holder name, account number, account type, and balance.
Search by Account Number: Users can search for an account by providing its account number. If the account is found, its details are displayed.
Deposit Amount: Users can deposit funds into an existing account by providing the account number and the amount to deposit.
Withdraw Amount: Users can withdraw funds from an existing account by providing the account number and the amount to withdraw. The code ensures that the balance doesn't go below the minimum required balance for the specific account type.
Remove Account: Users can delete an existing account by providing its account number.
The application runs in a loop, allowing users to perform multiple operations until they choose to exit the program.
