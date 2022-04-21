# Choose_Your_Own_Adventure
A simple choose your own adventure game

while True:
    answer = input ("A simple choose your own adventure game. Would you like to play? (yes/no) ")

    if answer == "yes":

        answer = input("Salad or Brownie?")
        if answer == "Brownie":
            answer = input("Yummy, would you like a drink? (yes/no)")

            if answer == "yes":
                print("Enjoy")
            else:
                print("You're going to be thirsty!")

        elif answer == "Salad":
            print("Healthy Choice!")

        else:
            print("That's not an option")
    else:
        print("That's too bad!")
        break
