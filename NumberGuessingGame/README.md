# Number Guessing Game

An interactive console-based Java game where the program generates a random number between 1 and 100 and gives hints until the user guesses it right.

## Game Rules & Test Cases
- **Range Check (Test 1):** Generates a random number between 1 and 100.
- **Cold Hint (Test 2):** If the guess is more than 10 away from the number (e.g., number = 50, guess = 30), returns `Cold`.
- **Hot Hint (Test 3):** If the guess is within 10 of the number (e.g., number = 50, guess = 49), returns `Hot`.
- **Exact Match (Test 4):** If the guess matches the number (e.g., number = 50, guess = 50), returns `Right`.
- **Loop & Exit Control (Test 5 & 6):** Uses a `while` loop to keep asking for guesses and `break` to exit as soon as the user guesses correctly.

## How to Run
```bash
javac NUmberGuessingGame.java
java NUmberGuessingGame
```
