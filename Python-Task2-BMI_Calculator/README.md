#OIBSIP

# BMI Calculator 🏋️

## 📌 Project Overview

The **BMI Calculator** is a Python application that calculates a user's **Body Mass Index (BMI)** based on their weight and height. It then classifies the BMI into standard health categories such as Underweight, Normal, Overweight, and Obese.

This project was developed as part of the **Oasis Infobyte Internship (OIBSIP)**.

---

## 🎯 Objective

Build a Python application that calculates a user's BMI and provides health classification based on the calculated value.

---

## ✨ Features

### Beginner Version

* User-friendly command-line interface
* Accepts weight (kg) and height (m)
* Calculates BMI using the standard formula
* Displays BMI rounded to two decimal places
* Classifies BMI into:

  * Underweight
  * Normal Weight
  * Overweight
  * Obese
* Input validation for invalid or negative values

### Advanced Version

* GUI built using Tkinter
* Simple and attractive interface
* Color-coded BMI results
* Save BMI records for multiple users
* Store records using SQLite or CSV
* Display BMI history using Matplotlib
* Error handling for database operations

---

## 🧮 BMI Formula

BMI = Weight (kg) / Height² (m²)

---

## 🛠️ Technologies Used

* Python
* Tkinter
* SQLite / CSV
* Matplotlib

---

## 📂 Project Structure

```
BMI-Calculator/
│── main.py
│── bmi_calculator.py
│── database.db
│── records.csv
│── README.md
```

---

## 🚀 How to Run

1. Clone the repository.
2. Open the project folder.
3. Run the program:

```bash
python main.py
```

---

## 📊 BMI Categories

| BMI Range      | Category      |
| -------------- | ------------- |
| Below 18.5     | Underweight   |
| 18.5 – 24.9    | Normal Weight |
| 25.0 – 29.9    | Overweight    |
| 30.0 and Above | Obese         |

---

## 📸 Output

The application displays:

* Weight
* Height
* BMI Value
* Health Category

For the GUI version:

* Interactive window
* Color-coded result
* BMI history graph

---

## 📈 Future Enhancements

* Export reports as PDF
* User authentication
* Cloud database integration
* Mobile application version

---

## 👩‍💻 Author

**Saniya Syed**

B.Tech – Artificial Intelligence & Machine Learning (AIML)

---

## 📜 License

This project is created for educational and internship purposes under the Oasis Infobyte Internship Program.
