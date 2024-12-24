# Online Banking System

Welcome to the Online Banking System! This application allows users to manage multiple types of bank accounts, including Checking Accounts, Saving Accounts, and Loan Accounts. Customers can perform essential banking operations like deposit, withdrawal, and balance enquiry, while administrators can manage customer data.

---

## 🖋 Table of Contents
1. [Overview](#-overview)
2. [Features](#-features)
3. [Screenshots](#-screenshots)
4. [Getting Started](#-getting-started)
5. [Dependencies](#-dependencies)
6. [User Credentials](#-admin-and-dummy-user-credentials)

---

## 📜 Overview

The **Online Banking System** provides users with the ability to create and manage multiple accounts, perform transactions, and track balances. The system includes various account types, each with unique functionalities:

- **Checking Accounts**: Support overdrafts, with a specified credit limit.
- **Saving Accounts**: Offer interest on the account balance, credited monthly based on the interest rate.
- **Loan Accounts**: Allow loans with monthly interest debited based on the loan balance and interest rate.

Customers can review their transactions and account balances. Administrators can manage all customer data and view the details and transaction history of all accounts.

---

## ✨ Features

- **Account Management** 🏦:
  - Create and manage multiple types of accounts: Checking, Saving, and Loan.
  - Perform transactions like deposit, withdrawal, and balance enquiry.

- **Transaction History** 💳:
  - Track and store transaction history for each account.

- **Account Types** 🔄:
  - **Checking Account**: Allows overdrafts up to a credit limit.
  - **Saving Account**: Credits balance with monthly interest based on the account balance and interest rate.
  - **Loan Account**: Debits balance with monthly interest based on the principal amount, interest rate, and loan duration.

- **Admin Panel** 💻:
  - Administrators can manage customer data and view transaction history and details of each account.

---

## 📸 Screenshots

![Home Page Screenshot]()  

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/USMAN-FAIZYAB-KHAN/Banking-System.git
   cd Banking-System
   ```

2. **Install Django**
   
   Use `pip` to install Django if not already installed:
   
   ```bash
   pip install django
   ```

4. **Run the Development Server**
   
   Start the application with the following command:
     
   ```bash
   python manage.py runserver
   ```

6. **Access the Application**
   
   Open your browser and navigate to:
   
   ```
   http://127.0.0.1:8000
   ```

---

## 📦 Dependencies

The project is built with the following dependency:

- **Django**: Backend framework.

---

Understood! Here's a more balanced version with a few emojis for a cleaner look:

---

## 🗝️ Admin & Dummy User Credentials

### **👑 Admin Credentials**  
- **Username**: Admin  
- **Password**: 12345678  

### **👥 Dummy Users**  
For testing purposes, you can use the following dummy users:  

- **Username**: Usman Faizyab  
  - **Password**: 1234  
  - **PIN**: 1234 (All accounts share the same PIN)

- **Username**: Muhammad Owais  
  - **Password**: 1234  
  - **PIN**: 1234 (All accounts share the same PIN)

- **Username**: Syed Abdul Basit  
  - **Password**: 1234  
  - **PIN**: 1234 (All accounts share the same PIN)

---

Enjoy using the **Online Banking System**! Feel free to contribute, suggest improvements, or provide feedback. 😊
