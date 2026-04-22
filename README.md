🏧 ATM Simulator System
A desktop-based banking simulator built with Java and Swing that replicates core ATM operations including authentication, withdrawals, deposits, and balance inquiries.

📌 Overview
The ATM Simulator System is a Java desktop application designed to mimic real-world ATM functionality. It provides a graphical user interface for users to securely log in and perform common banking transactions, with data persisted through file handling.

✨ Features

User Authentication — Secure PIN-based login system to validate account holders
Withdrawal — Withdraw funds with balance validation and overdraft prevention
Deposit — Deposit amounts and instantly update account balance
Balance Inquiry — View current account balance at any time
Session Management — Logout functionality to end banking sessions securely


🛠️ Tech Stack
LayerTechnologyLanguageJavaUI FrameworkJava SwingStorageFile Handling (I/O)ArchitectureObject-Oriented (OOP)

🗂️ Project Structure
ATM-Simulator/
│
├── src/
│   ├── Main.java               # Entry point
│   ├── ATM.java                # Core ATM logic
│   ├── Account.java            # Account model
│   ├── Authentication.java     # Login & PIN validation
│   ├── Transaction.java        # Withdrawal, deposit, inquiry
│   └── FileHandler.java        # File read/write operations
│
├── data/
│   └── accounts.txt            # Persistent account data
│
└── README.md

🚀 Getting Started
Prerequisites

Java Development Kit (JDK) 8 or higher
Any Java IDE (IntelliJ IDEA, Eclipse, NetBeans) or command line

Running the Application
Using an IDE:

Clone or download the repository
Open the project in your preferred Java IDE
Run Main.java as the entry point

Using the Command Line:
bash# Compile
javac src/*.java -d out/

# Run
java -cp out/ Main

🖥️ Usage

Launch the application — the login screen will appear
Enter your Account Number and PIN to authenticate
Select an operation from the main menu:

Check Balance — displays current account balance
Deposit — enter an amount to add to your account
Withdraw — enter an amount to deduct (subject to available balance)
Logout — exit the current session


Transactions are saved automatically via file handling


🏗️ Architecture
The project follows a modular object-oriented design:

Model Layer — Account.java encapsulates account data and business rules
Logic Layer — ATM.java and Transaction.java handle operation flow
Persistence Layer — FileHandler.java manages reading/writing account records
UI Layer — Swing components handle all user interaction and display
Authentication — Handled separately to enforce single-responsibility principle


📄 License
This project is intended for educational purposes. Feel free to use and modify it for learning or personal projects.

👤 Author
Developed as a Java desktop application project demonstrating GUI programming, file I/O, and object-oriented design principles.
