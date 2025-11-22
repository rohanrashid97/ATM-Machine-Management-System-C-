# 🏧 ATM Machine Management System (C++)

A console-based ATM Machine Management System built using **C++** and compiled with **GCC** in CodeBlocks. The system provides core ATM functionalities such as account verification, balance inquiry, withdrawal, deposit, transaction help, and secure exit options.

This project was developed as part of the B.Sc. Engineering program (Intake 41, BUBT).  
📄 Reference: *ATM Project Report* :contentReference[oaicite:2]{index=2}

---

## 🚀 Project Overview
Traditional banking requires users to visit counters for transactions. This project simplifies core ATM operations through a console program.  
According to the report’s abstract (page 6) :contentReference[oaicite:3]{index=3}, the system aims to:
- Provide balance inquiry  
- Withdraw cash  
- Deposit cash  
- Offer help information  
- Validate account number & password  

It also introduces a new idea: **reporting lost ATM cards directly from the machine**, reducing delays.

---

## ⭐ Key Features
### ✔ Account Verification
User enters:
- Account Number  
- Password  
If incorrect, shown error message (page 21) :contentReference[oaicite:4]{index=4}.

### ✔ Main Menu Options (page 13)  
1. **Inquire Balance**  
2. **Withdraw**  
3. **Deposit**  
4. **Quit**

### ✔ Balance Inquiry
Displays current account balance (page 19) :contentReference[oaicite:5]{index=5}.

### ✔ Withdraw Money
Allows user to withdraw custom amount (page 20)  
Shows:
- Withdrawal amount  
- Remaining balance  

### ✔ Deposit Money
User can deposit money (page 20)  
Shows:
- Deposit amount  
- Updated balance  

### ✔ Help Menu (page 21)
Provides solutions for:
- Wrong password  
- Suspected hacking  
- Money deducted but not received  

---

## 🧰 Development Environment
From the report (page 10) :contentReference[oaicite:6]{index=6}:

| Component | Details |
|----------|---------|
| IDE | CodeBlocks 20.03 |
| Language | C++ |
| Compiler | GCC |
| OS | Windows 10 |
| CPU | Intel Core i7 |
| RAM | 8 GB |
| Storage | 512GB SSD |

---

## 🧠 System Flow (Flowchart Reference)
The flowchart (page 17) :contentReference[oaicite:7]{index=7} shows:
1. Homepage  
2. Transaction Menu  
3. Account Number → Password  
4. Main Screen (options)  
5. Transaction execution  
6. Back to main screen  
7. Quit  

---

## 📂 File Structure (Suggested)
