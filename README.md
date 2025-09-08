# Restaurant Management System

A **Restaurant Management System** built for OS Lab using **Bash scripting**.  
This system allows users to register, login, order food, apply discounts, and manage their account.  
Admins can monitor and manage users, simulating a simple restaurant management workflow.

---

## 🏷️ Features

### For Users:
- **Registration:**  
  - Enter name, phone number, username, and password  
  - Phone validation: Bangladesh numbers (013–019, 11 digits)  
  - Password must be at least 6 characters

- **Login:**  
  - Secure login with username & password  
  - Maximum 3 attempts allowed

- **Account Management:**  
  - Change username  
  - Change password

- **Order Food:**  
  - Menu segments: Breakfast, Lunch, Lunch Package, Snacks, Dinner  
  - Select quantity for each item  
  - Apply coupon codes for instant discount: `BD10`, `BD20`, `BD50`  
  - Progressive discount system based on total bill:  
    - 10% for >1000 BDT  
    - 15% for >2000 BDT  
    - 20% for >5000 BDT  
  - Invoice generated automatically with: items, quantities, price, discounts, total

### For Admins:
- Login using default credentials  
- View all registered users  
- Delete any user account  

---

## 📦 Menu Items

**Breakfast:**  
Khichuri, Paratha, Egg Toast, Vegetable Sandwich, Milk Tea  

**Lunch:**  
Chicken Curry, Egg Curry, Rice, Dal  

**Lunch Packages:**  
Rice + Vegetable + Egg Curry + Dal, Fried Rice + Chicken Curry + Dal  

**Snacks:**  
Samosa, Roll, Burger, Chotpoti  

**Dinner:**  
Fried Rice, Grilled Chicken, Vegetable Stir Fry, Soup  

---


