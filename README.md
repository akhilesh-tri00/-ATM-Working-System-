ATM-Working-System

This project is a Python-based ATM simulation built using Object-Oriented Programming (OOP) principles and the abc module for abstraction.
It demonstrates key concepts like abstract classes, encapsulation, validation, and user interaction through a simple command-line ATM system.

#Features:-
-PIN Authentication – Users must enter a valid PIN before accessing services.
-Withdraw – Withdraw money if sufficient balance is available.
-Deposit – Deposit money into your account.
-Balance Inquiry – Check your current account balance.
-PIN Change – Update your ATM PIN securely.
-Transaction Receipt – Displays receipt for each transaction.
-Encapsulation – Private attributes used for PIN and balance.
-Abstract Class Implementation – ATM interface enforced via Python's abc module.

#Code Structure:-
ATM (Abstract Base Class):
 -> (Defines the structure with abstract methods)
-withdraw()
-deposit()
-show_balance()
-receipt()
-pin_change()

Server (Concrete Class):
 -> (Implements all abstract methods and handles)
-PIN validation
-Balance management
-Transactions and receipts

#Main Program
 -> Provides a command-line interface for the user to interact with the ATM...

