# -Number-Guessing-Game-Python-
---------------------------------------------------------------------------------------------------------------------------------------------------------------------

---

### 🎮 Number Guessing Game (Python)

```python
import random

def guess_the_number():
    number_to_guess = random.randint(1, 100)
    attempts = 0

    print("🎉 Welcome to the Number Guessing Game!")
    print("I'm thinking of a number between 1 and 100.")
    
    while True:
        try:
            guess = int(input("Enter your guess: "))
            attempts += 1

            if guess < number_to_guess:
                print("Too low! Try again. 🔽")
            elif guess > number_to_guess:
                print("Too high! Try again. 🔼")
            else:
                print(f"🎯 Congratulations! You guessed the number in {attempts} attempts.")
                break
        except ValueError:
            print("⚠️ Please enter a valid number.")

if __name__ == "__main__":
    guess_the_number()
```

---

### 🧠 How It Works:

* The computer randomly selects a number between 1 and 100.
* The player guesses until they get it right.
* Feedback is given if the guess is too high or too low.
* It keeps track of how many guesses were made.

---

# ------------------------------------------------------------
# Number Guessing Game
# Author: Aditya Kumar Jha
# Copyright (c) 2025 Aditya Kumar Jha
# All rights reserved.
# ------------------------------------------------------------

"""
This software is provided for educational and non-commercial use only.
Unauthorized reproduction or distribution is strictly prohibited.
"""

