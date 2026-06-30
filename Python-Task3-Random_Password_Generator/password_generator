import random
import string

def generate_password(length, use_upper, use_lower, use_digits, use_symbols):
    characters = ""
    password = []

    if use_upper:
        characters += string.ascii_uppercase
        password.append(random.choice(string.ascii_uppercase))

    if use_lower:
        characters += string.ascii_lowercase
        password.append(random.choice(string.ascii_lowercase))

    if use_digits:
        characters += string.digits
        password.append(random.choice(string.digits))

    if use_symbols:
        symbols = "!@#$%^&*()-_=+[]{}|;:,.<>?/"
        characters += symbols
        password.append(random.choice(symbols))

    while len(password) < length:
        password.append(random.choice(characters))

    random.shuffle(password)
    return "".join(password)


def main():
    print("=" * 45)
    print("      RANDOM PASSWORD GENERATOR")
    print("=" * 45)

    while True:
        try:
            length = int(input("\nEnter password length (minimum 8): "))

            if length < 8:
                print("Error: Password length must be at least 8.")
                continue

            print("\nChoose character types (Y/N):")

            upper = input("Include Uppercase Letters? (Y/N): ").strip().lower() == "y"
            lower = input("Include Lowercase Letters? (Y/N): ").strip().lower() == "y"
            digits = input("Include Numbers? (Y/N): ").strip().lower() == "y"
            symbols = input("Include Symbols? (Y/N): ").strip().lower() == "y"

            selected = sum([upper, lower, digits, symbols])

            if selected < 2:
                print("Error: Select at least TWO character types.")
                continue

            password = generate_password(length, upper, lower, digits, symbols)

            print("\nGenerated Password:")
            print(password)

            again = input("\nGenerate another password? (Y/N): ").strip().lower()

            if again != "y":
                print("\nThank you for using the Password Generator!")
                break

        except ValueError:
            print("Error: Please enter a valid number.")


if __name__ == "__main__":
    main()
