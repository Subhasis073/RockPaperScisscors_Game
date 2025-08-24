**1. Description**
A Python implementation of the classic Rock, Paper, Scissors game where you play against the computer. Choose your move by typing a number, and the computer randomly selects its own. The program determines and displays who won, lost, or if it’s a draw.

**2. How It Works**
The player chooses rock, paper, or scissors by entering 0, 1, or 2.

The computer picks its move randomly.

Both choices are displayed using ASCII art.

The winner is decided with game rules and shown in the console.

**3. How to Play**
Run the script in a Python environment.

Enter 0 for Rock, 1 for Paper, or 2 for Scissors when prompted.

See the computer’s choice and result (win/lose/draw).

**4. Operators and Functions Used**

Operators:

= (Assignment): Assigns values to variables such as rock, user_choice, computer_choice, etc.

>=, <=, <, > (Comparison): Used to check the validity of user input and decide game outcomes.

== (Equality): Compares choices to determine the winner, loser, or if it’s a draw.

and (Logical AND): Used to check multiple conditions together.

[] (Indexing): Retrieves the selected ASCII art from the list.


Functions:

print(): Displays messages, ASCII art, and results.

input(): Gets user input as a string.

int(): Converts the user’s input from string to integer.

random.randint(): Randomly generates the computer’s choice.

f-string (f""): Formats the output message with variables for user/computer choices.

int(): Converts the user’s input from string to integer.

random.randint(): Randomly generates the computer’s choice.
