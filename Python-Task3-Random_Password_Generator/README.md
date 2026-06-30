# 🔐 Random Password Generator

## 📌 Project Overview

The **Random Password Generator** is a Python application that creates strong and secure passwords based on user-defined preferences. Users can choose the password length and select the types of characters to include, such as uppercase letters, lowercase letters, numbers, and symbols.

This project was developed as part of the **Oasis Infobyte Internship (OIBSIP)**.

---

## 🎯 Objective

Develop a Python application that generates random passwords based on user-specified criteria while ensuring password strength and security.

---

## ✨ Features

### Beginner Version

* Command-line interface
* User specifies password length (minimum 8 characters)
* Choose character types:

  * Uppercase Letters (A-Z)
  * Lowercase Letters (a-z)
  * Numbers (0-9)
  * Symbols (!@#$%^&*)
* Ensures at least two character types are selected
* Generates a secure random password
* Input validation for invalid values
* Option to generate multiple passwords without restarting

### Advanced Version

* GUI built using Tkinter or PyQt5
* Password length control using slider or spinbox
* Cryptographically secure password generation using the `secrets` module
* Password strength indicator (Weak / Medium / Strong)
* Guarantees at least one character from each selected type
* Copy generated password to clipboard using `pyperclip`
* Option to exclude ambiguous characters (0, O, l, 1)
* Displays the last five generated passwords during the session

---

## 🛠️ Technologies Used

* Python
* random
* string
* secrets
* tkinter
* pyperclip

---

## 📂 Project Structure

```text
Random-Password-Generator/
│── password_generator.py
│── README.md
```

---

## 🚀 How to Run

1. Clone the repository.
2. Open the project folder.
3. Run the program:

```bash
python password_generator.py
```

---

## 📖 How It Works

1. Enter the desired password length (minimum 8).
2. Choose the character types to include.
3. The program validates your input.
4. A strong random password is generated and displayed.
5. Choose whether to generate another password.

---

## 💡 Example Output

```text
=========================================
      RANDOM PASSWORD GENERATOR
=========================================

Enter password length (minimum 8): 12

Include Uppercase Letters? (Y/N): y
Include Lowercase Letters? (Y/N): y
Include Numbers? (Y/N): y
Include Symbols? (Y/N): y

Generated Password:
A7@mQ2!xLp#8
```

---

## 📈 Future Enhancements

* Password saving with encryption
* Export generated passwords securely
* Dark mode GUI
* Password expiration reminder
* Custom symbol selection

---

## 👩‍💻 Author

**Saniya Syed**

B.Tech – Artificial Intelligence & Machine Learning (AIML)

---

## 📜 License

This project was created for educational purposes as part of the **Oasis Infobyte Internship (OIBSIP)**.
