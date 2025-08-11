# Bank Account Simulation

## Objective
A simple Java console-based program to simulate basic bank operations such as deposit, withdrawal, balance check, and viewing transaction history using **Object-Oriented Programming (OOP)** concepts.

## Features
- **Account Creation** with account holder name and initial balance.
- **Deposit** and **Withdraw** operations with validation.
- **Balance Inquiry** to check current balance.
- **Transaction History** to display all deposits and withdrawals.
- Menu-driven interface for easy navigation.

## Tools & Technologies
- **Language:** Java
- **IDE:** Eclipse IDE for Java Developers
- **JDK:** Java 8 or higher

## How to Run in Eclipse

1. **Install Prerequisites**
   - Install JDK (Java Development Kit).
   - Install Eclipse IDE for Java Developers.

2. **Create a New Java Project**
   - Open Eclipse.
   - Go to **File → New → Java Project**.
   - Enter Project Name: `BankSimulation`.
   - Click **Finish**.

3. **Create a Package**
   - Right-click `src` → **New → Package**.
   - Name it: `com.bankapp`.

4. **Add Java Classes**
   - Right-click the package → **New → Class**.
   - Create `Account` (without `main` method) → Paste Account class code.
   - Create `BankAccountSimulation` (with `main` method) → Paste main program code.

5. **Save and Build**
   - Save all files (`Ctrl + S`).
   - Eclipse builds automatically.

6. **Run the Program**
   - Right-click `BankAccountSimulation.java` → **Run As → Java Application**.
   - Enter inputs in the **Console** view.

## Example Output

Enter account holder name: John
Enter initial balance: ₹5000

----- BANK MENU -----

- Deposit
- Withdraw
- Check Balance
- Transaction History
- Exit
- Enter your choice: 1
- Enter deposit amount: ₹2000
- Deposit successful. Current balance: ₹7000
