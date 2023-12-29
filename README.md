# 1D-Arrays-Class-Methods
first project using arrays and class methods

Scenario: The Number Guessing Game is a program in which users have a certain number of
attempts to estimate a number between 1 and 10; and mainly focuses on the usage of 1-D
Arrays and Class Methods. Users enter their predictions, and the program responds by telling
whether the actual number is greater or lesser than the guess. If the player correctly guesses
the proper number within the allotted number of attempts, they win. Otherwise, the program will
show you the right answer. This game encourages the user to use their deduction skills, and
successfully guess the number.


Input:
- Guessed number from the user (3 times/attempts at most)
Algorithm:
1. Start the game by generating a random number between 1 and 10 and setting the
maximum number of attempts to 3.
2. Display a welcome message and the rules of the game to the player.
3. Prompt the player to enter their guess.
4. Process the player's guess.
5. Check if the guess is correct:
● If the guess matches the random number, display a congratulations message and
end the game.
● If the guess is lower than the random number, inform the player that the number
is higher.
● If the guess is higher than the random number, inform the player that the number
is lower.

6. Repeat steps 3-5 until the player guesses the correct number or runs out of attempts.
7. If the player runs out of attempts without guessing the correct number, display the
correct answer.
8. End the program


Process/Predefined Methods used:
● Math.random(): Used to generate a random number between 0 and 1.
● input.nextInt(): Read an integer input from the user.
● System.out.print(): Prints a message.
● input.nextInt(): Reads an integer inputted from the user
