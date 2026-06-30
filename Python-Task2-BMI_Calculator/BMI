# BMI Calculator

def calculate_bmi(weight, height):
    """Calculate BMI."""
    return weight / (height ** 2)


def classify_bmi(bmi):
    """Return BMI category."""
    if bmi < 18.5:
        return "Underweight"
    elif bmi < 25:
        return "Normal Weight"
    elif bmi < 30:
        return "Overweight"
    else:
        return "Obese"


def main():
    print("=" * 40)
    print("        BMI CALCULATOR")
    print("=" * 40)

    try:
        # Get user input
        weight = float(input("Enter your weight (kg): "))
        height = float(input("Enter your height (m): "))

        # Validate input
        if weight <= 0 or height <= 0:
            print("\nError: Weight and height must be greater than zero.")
            return

        # Calculate BMI
        bmi = calculate_bmi(weight, height)

        # Determine category
        category = classify_bmi(bmi)

        # Display result
        print("\n========== BMI RESULT ==========")
        print(f"Weight        : {weight:.2f} kg")
        print(f"Height        : {height:.2f} m")
        print(f"BMI           : {bmi:.2f}")
        print(f"Health Status : {category}")
        print("================================")

    except ValueError:
        print("\nError: Please enter valid numeric values only.")


if __name__ == "__main__":
    main()
