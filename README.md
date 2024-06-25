# CODSOFT
Java programming some problems solutions. 

1.**This Java program implements a simple number guessing game.**
 Here's a brief summary of how it works:

Initialize Random Number: The program generates a random number between 1 and 100.
User Input: It repeatedly prompts the user to guess the number.
Comparison:
If the user's guess is correct, it prints a congratulatory message and exits the loop.
If the guess is too high, it informs the user that the guess is higher than the target and asks them to guess again.
If the guess is too low, it informs the user that the guess is lower than the target and asks them to guess again.
Loop: The game continues until the user guesses the correct number.

2.**This Java program simulates a basic ATM system.**
 Here is a brief summary of its functionality:

Login: The user is prompted to enter a username and PIN. After entering these details, a welcome message is displayed.
Main Menu: The user is presented with a menu of options:
Withdraw: The user can enter an amount to withdraw. If there are sufficient funds, the balance is decreased, and the transaction is recorded in the history.
Deposit: The user can enter an amount to deposit. If the amount is less than or equal to 50,000, the balance is increased, and the transaction is recorded in the history.
Transfer: The user can transfer an amount to another account by entering the recipient's username. The balance is decreased, and the transaction is recorded in the history.
Transaction History: The user can view a list of all transactions performed during the session.
Exit: The user can choose to exit the program.
Continue or Exit: After each transaction, the user is asked if they want to continue or exit. If they choose to continue, the main menu is displayed again.
Close Scanner: The scanner is closed when the user chooses to exit