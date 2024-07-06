**Number Guessing Game**
Summary:

**This Java program implements a simple number guessing game where the user attempts to guess a randomly generated number between 1 and 100.**
Functionality:

    Initialize Random Number:
        The program generates a random number.
    User Input:
        Prompt the user to guess the number.
    Comparison:
        If the guess is correct, display a congratulatory message and exit.
        If the guess is too high or too low, provide feedback and prompt the user to guess again.
    Loop:
        Continues until the user guesses the correct number.

**Basic ATM System**
Summary:

**This Java program simulates a basic ATM system with user authentication and transaction capabilities.**
Functionality:

    Login:
        User enters a username and PIN to access the system.

    Main Menu Options:
        Withdraw: User can withdraw a specified amount if funds are sufficient.
        Deposit: User can deposit an amount (up to 50,000).
        Transfer: User can transfer funds to another account.
        Transaction History: View all transactions made during the session.
        Exit: Option to leave the program.

    Continuation:
        After each transaction, the user is prompted to continue or exit.

**Quiz Application**
Summary:

**This Java program is a quiz application that asks multiple-choice questions with a timer for each question.**
Functionality:

    Question Class:
        Represents a quiz question with options and correct answer.

    Quiz Class:
        Fields: Manages questions, user score, current question index, timer, and user answers.
        start(): Initiates the quiz, displays questions, handles user input, and updates score.
        displayQuestion(): Shows the current question and options.
        startTimer(): Starts a 10-second timer per question.
        stopTimer(): Stops the timer.
        displayResult(): Displays quiz score and answers summary.
        Main Method: Sets up questions, initializes Quiz object, and starts the quiz.

