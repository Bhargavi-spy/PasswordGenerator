import string
import random
print("enter exit if you select the required data")
# Getting password length
while True:
    try:
        length = int(input("Enter password length: "))
        if length <= 0:
            print("Password length should be a positive integer.")
            continue
        break
    except ValueError:
        print("Please enter a valid integer for password length.")

characterList = ""

while True:
    print('''Choose character set for password from these: 
    1. Letters
    2. Digits
    3. Special characters
    4. Exit''')

    choice = input("Pick a number: ").strip()

    if choice == '':
        print("Input cannot be empty. Please enter a number.")
        continue

    if not choice.isdigit():
        print("Please enter a valid number.")
        continue

    choice = int(choice)

    if choice == 1:
        if string.ascii_letters not in characterList:
            characterList += string.ascii_letters
            print("Letters added.")
        else:
            print("Letters already added.")
    elif choice == 2:
        if string.digits not in characterList:
            characterList += string.digits
            print("Digits added.")
        else:
            print("Digits already added.")
    elif choice == 3:
        if string.punctuation not in characterList:
            characterList += string.punctuation
            print("Special characters added.")
        else:
            print("Special characters already added.")
    elif choice == 4:
        if characterList == "":
            print("No character sets selected yet! Please choose at least one.")
            continue
        else:
            break
    else:
        print("Please pick a valid option!")

password = [random.choice(characterList) for _ in range(length)]
print("The random password is " + "".join(password))
