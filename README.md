# Personal-Manager
An app to assist with personal management.

Features:
1. Financial Manager
2. Schedule Manager
3. Inventory Manager

============================================================================
0.0 Dashboard
- Display user's Shopping List
- Display user's upcoming Tasks or Events.
- Display user's Primary Wallet's balance.

============================================================================
1.0 Financial Manager
This section will handle everything regarding a person's finances; Income, Expenses, Bills, Wallets

    1.1 Income
- User can manually insert the amount of income.
- User states to which "Wallet" the money goes. Primary Wallet is selected by default is Wallet is not chosen.

    1.2 Expenses
- User can insert the transaction details.
- User can choose the category of the expense transaction.
- User choose which "Wallet" is handling that transaction. Primary Wallet is selected by default is Wallet is not chosen.

    1.3 Bills
- User register their bills and it's date-for-payment.
- The manager reminds user when a bill is due.

    1.4 Wallets
- A concept of "banks". A single user can have several banks or, in this case, "Wallets".
- Holds the amount of money the user has in their bank account balance.
- Will be used for transactions during an Income or Expense transaction.
- A user can set a Wallet as "Primary Wallet". When handling Income or Expense transactions, "Primary Wallet" is selected by default.

    1.5 Wallet Transfer
- Transfers amount between user's Wallets.
============================================================================
2.0 Schedule Manager
- This section will handle everything regarding a person's schedule; Events, Appointments, Tasks.
- A Dashboard exists to display the user's upcoming Tasks or Events.

    2.1 Events
- User can register upcoming events or appointments to be added to their calendar.

    2.2 Tasks
- User register tasks and its due.
- The manager reminds user of their tasks.

    2.3 Calendar
- Holds all Events and Tasks list, in a easy-to-read manner.
- Reminds user of their Events and Tasks.

============================================================================
3.0 Inventory Manager
This section will handle everything regarding a person's inventory; Assets, Tools, Grocery List, Shopping List.

    3.1 Inventory Stock
- The inventory list of items the user has.
- Can be categorised. (Such as "Hardware", "Grocery", "Assets", etc.)
- Categories are, preferably, customizable; with a few existing defaults.

    3.2 Shopping/Grocery List
- A list for of items that the user wishes to buy.

