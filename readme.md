# ☕ OOP Coffee Machine (Python)

This project is an **Object-Oriented Programming (OOP)** based coffee machine simulation built in Python.  
It mimics the behavior of a real coffee machine by managing resources, processing payments, and serving coffee based on user input.

This project is part of learning **OOP concepts through hands-on implementation** rather than just theory.

---

## 🚀 Features

- Choose between **espresso, latte, and cappuccino**
- Check machine **resource report**
- Handle **coin-based payments**
- Deduct resources after making coffee
- Turn off the machine anytime
- Clean separation of responsibilities using OOP

--

## 🧠 OOP Concepts Used

- **Classes & Objects**
- **Encapsulation**
- **Single Responsibility Principle**
- **Object Interaction**
- **State Persistence**

Each class is responsible for a single role, just like real-world systems.

---

## 🗂 Project Structure

oop-coffee-machine/
│
├── main.py # Main controller logic
├── menu.py # Menu and Drink classes
├── coffee_maker.py # CoffeeMaker class (resources & coffee)
├── money_machine.py # MoneyMachine class (payments)
└── README.md

yaml
Copy code

---

## ⚙️ How It Works

1. User selects a drink (`espresso`, `latte`, `cappuccino`)
2. Menu returns a **Drink object**
3. CoffeeMaker checks if resources are sufficient
4. MoneyMachine processes payment
5. Coffee is made and resources are deducted
6. Machine continues running until turned off

---

## ▶️ How to Run

Make sure Python is installed on your system.

```bash
python main.py
🧪 Example Usage
text
Copy code
Welcome to the Coffee Machine!
What would you like? (espresso/latte/cappuccino): latte
Please insert coins.
Here is your latte ☕️. Enjoy!
📝 Commands
espresso / latte / cappuccino → Order coffee

report → Show remaining resources and money

off → Turn off the machine

🎯 Learning Outcome
This project helped in understanding:

Why objects should represent real-world entities

How classes interact with each other

Why passing objects is better than passing raw data

How OOP makes programs scalable and maintainable

🙌 Acknowledgment
Inspired by the 100 Days of Python course by Dr. Angela Yu.
Built with the intention of learning OOP through practice and debugging.

🧑‍💻 Author
Mohit Kunwar

Learning Python, OOP, and DSA step by step 🚀

