# Rock Paper Scissors Game
An interactive classic game of Rock Paper Scissors against the computer in the Python Programming Language. Implementing features such as user input, random number generation, and conditional statement.

# Code 
import random

usercount = 0
computercount = 0

options = ["rock", "paper", "scissors"]

while True:
  userinput = input("Rock, Paper, Scissors? Type 'quit' to exit/scoreboard: ").lower()
  if userinput == "quit": 
    break 

  if userinput not in options:
    print("Invalid Option. Please Try Again: ")
    continue
  
  computer = random.randint(0,2)
  computer_picks = options[computer]
  print("The Computer Picked: ", computer_picks)
  
  if userinput == "rock" and computer_picks == "scissors":
    print ("You won!")
    usercount += 1
  
  elif userinput =="paper" and computer_picks =="rock":
    print ("You won!")
    usercount += 1

  elif userinput =="scissors" and computer_picks =="paper":
    print ("You won!")
    usercount += 1
    
  elif userinput == computer_picks:
    print ("Tie! Try Again")
    
  else:
    print("You lost! Try Again")
    computercount += 1
    
print("You won", usercount, "times")
print("The computer won", computercount, "times")
print("Thank You For Playing!")
