Lab02 - ATM Console Application
Summary
This console application simulates the functionality of an ATM (Automated Teller Machine). It allows users to perform basic banking operations such as checking their account balance, making withdrawals, and depositing funds.

Visuals
ATM Console Application

Usage
Clone or download the Lab02 project repository.
Open the solution in Visual Studio.
Build the solution to restore NuGet packages and compile the code.
Run the project to start the ATM console application.
The application will display a menu with the following options:
1. View Balance: This option allows you to check your account balance. Upon selecting this option, the current balance will be displayed on the console.
2. Withdraw: Use this option to withdraw funds from your account. Enter the amount you wish to withdraw when prompted. The application will validate the amount and ensure it does not exceed your account balance. If the withdrawal is successful, the new balance will be displayed.
3. Deposit: Select this option to deposit funds into your account. Enter the amount you want to deposit when prompted. The application will validate the amount and update your account balance accordingly. The new balance will be displayed after a successful deposit.
4. Exit: Choosing this option will exit the application.
Example Walkthrough
Upon running the application, you will see the main menu.
Select option 1 to view your account balance. The current balance will be displayed.
Choose option 2 to make a withdrawal. Enter the amount you wish to withdraw.
If the amount is valid and within your account balance, the withdrawal will be successful, and the new balance will be shown.
Similarly, you can use option 3 to deposit funds into your account. Enter the amount to deposit, and the new balance will be displayed.
Repeat the above steps to perform additional operations or choose option 4 to exit the application.
Additional Details
The application ensures that withdrawal amounts are not negative or greater than the account balance.
Deposit amounts must be non-negative.
The balance variable is accessible from other parts of the code to facilitate testing.
The project includes a separate test project (Lab02Test) with unit tests to verify the functionality of the ATM application.
