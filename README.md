# Guessing_Game_Streamlit
A fun and interactive number guessing game built with Python and Streamlit. Guess a number between 1 and 100, and get instant feedback like "Warmer" or "Colder" to guide you toward the secret number. Play, restart, and enjoy the logic challenge!

### A Python-based number guessing game where the player attempts to identify a randomly selected number between 1 and 100.

#### Instead of giving standard responses like "Too high" or "Too low," the game provides temperature-based hints to make the experience more interactive:

- "WARM!" – if the first guess is within 10 digits of the target number

- "COLD!" – if the first guess is more than 10 digits away

#### For all following guesses:

- "WARMER!" – if the new guess is closer to the target than the previous guess

- "COLDER!" – if it’s farther away than the last attempt

- The game tracks all previous guesses using a list and counts the total number of attempts. Once the player correctly guesses the number, it displays a congratulatory message along with the number of tries taken.

#### Key concepts used in this project include:

- random.randint() for generating the secret number

- while loops to run the game continuously until the correct guess is made

- input() to collect user guesses

- abs() to measure the difference between the guesses and the target

#### This is a beginner-friendly project designed to reinforce understanding of:

- Loops and conditional logic

- List operations

