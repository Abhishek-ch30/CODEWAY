# Importing string and random modules
import string
import random
# Creating lists of ASCII letters, digits, punctuation, and whitespaces
ascii_letters = string.ascii_letters
digits = string.digits
punctuation = string.punctuation
whitespace = string.whitespace
# Combining all lists into a single list
all_characters = []
all_characters.extend(list(ascii_letters))
all_characters.extend(list(digits))
all_characters.extend(list(punctuation))
all_characters.extend(list(whitespace))
# Shuffling the combined list
random.shuffle(all_characters)

def main():
    option = input("Do you want to generate a strong password (Yes/No)? ").lower()

    if option == "yes":
        password_length = int(input("Enter the length of the password: "))
        if password_length < 8:
            print("Password length must be at least 8 characters.")
            return
# Displaying the generated password
        print('Generated password:', ''.join(all_characters[:password_length]))
    elif option == "no":
       print("Program terminated. Thank you!")
    else:
        print("Invalid input!!! Please enter Yes/No")
main()
