# DiceGame
import random

print("Welcome to the Dice Game!")

# Set up the rules of the game
print("Rules: Roll a dice and guess the number (1-6) it lands on.")
print("If you guess correctly, you win!\n")

# Get the user's guess
guess = int(input("Enter your guess (1-6): "))

# Roll the dice
dice_roll = random.randint(1, 6)

# Check if the user's guess is correct
if guess == dice_roll:
    print(f"\nThe dice landed on {dice_roll} - congratulations, you won!")
else:
    print(f"\nThe dice landed on {dice_roll} - sorry, you lost! Better luck next time.")
