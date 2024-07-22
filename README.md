# Prodigy-Infotech-Task-2
Task 2
import random
number_to_guess = random.randint(1, 10)
attempts = 0
while True:
    user_guess = int(input("Guess a number between 1 and 10: "))
    attempts += 1
    if user_guess == number_to_guess:
        print(f"Congratulations! You guessed the number in {attempts} attempts.")
        break
    elif user_guess > number_to_guess:
        print("Your guess is too high. Try again!")
    else:
        print("Your guess is too low. Try again!")
