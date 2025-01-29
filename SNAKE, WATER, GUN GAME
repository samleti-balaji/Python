import random

# Game- 1 for snake, -1 for water, and 0 for gun.

computer = random.choice([1, 0, -1])
youstr = input("Enter your choice: Snake(1), Water(-1), Gun(0): ")
youDict = {"s": 1, "w": -1, "g": 0}
reverseDict = {1: "Snake", -1: "Water", 0: "Gun"}

you = youDict[youstr]

print(f"you chose {reverseDict[you]}\n computer chose {reverseDict[computer]}")

if you == computer:
    print("It's a tie")
elif((computer - you) == -1 or (computer - you) == 2):
    print("You lose!")
else:
    print("You win!")

# else:

#     elif(computer == -1 and you == 1): # -2
#         print("You win!")

#     elif(computer == -1 and you == 0): # -1
#         print("You lose")

#     if(computer == 1 and you == -1): # 2
#         print("You lose!")
    
#     elif(computer == 1 and you == 0): # 1
#         print("You win!")

#     elif(computer == 0 and you == 1): # -1
#         print("You lose")

#     elif(computer == 0 and you == -1): # 1
#         print("You Win!")
#     else:
#         print("Something went wrong!")


# if((computer - you) == -1 or (computer - you) == 2):
#     print("You win!")
# else:
#     print("You lose!")
