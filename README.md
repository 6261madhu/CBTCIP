print("Welcome to the game!\n")
playing = input("Do you want to play? (yes/no): ").lower()

if playing != "yes":
    print("Maybe next time!")
    quit()

score = 0  # Initialize score

print("Okay! Let's play 😄")

# Question 1
print("\nQuestion 1:")
answer = input("What does CPU stand for? ").lower()
if answer == "central processing unit":
    print("Correct! 🎉")
    score += 1
else:
    print("Incorrect! The correct answer is 'Central Processing Unit'.")

# Question 2
print("\nQuestion 2:")
answer = input("What does CU stand for? ").lower()
if answer == "control unit":
    print("Correct! 🎉")
    score += 1
else:
    print("Incorrect! The correct answer is 'Control Unit'.")

# Question 3
print("\nQuestion 3:")
answer = input("What does RAM stand for? ").lower()
if answer == "random access memory":
    print("Correct! 🎉")
    score += 1
else:
    print("Incorrect! The correct answer is 'Random Access Memory'.")

# Final Score
print(f"\nYou've completed the quiz! Your score is: {score}/3.")
if score == 3:
    print("Excellent! You got all answers right! 🌟")
elif score == 2:
    print("Good job! Keep learning! 👍")
else:
    print("Don't worry, try again and you'll get there! 💪")
