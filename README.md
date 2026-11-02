# 🍔 Canteen Management System (C++)

## 📌 Project Overview

The **Canteen Management System** is a console-based application developed using C++. It helps customers view the available food menu, select food items, enter quantities, and generate a final bill automatically.

This project is developed using Object-Oriented Programming (OOP) concepts in C++ to demonstrate how classes, objects, encapsulation, constructors, and vectors can be used to build a simple real-world application.

## 🎯 Objectives

- To create a simple digital canteen ordering system.
- To display available food items with their prices.
- To allow customers to select food items and quantities.
- To calculate the total bill automatically.
- To understand the practical implementation of OOP concepts in C++.

## ✨ Features

- **Display Menu:** Shows available food items with their IDs and prices.
- **Place Order:** Allows customers to select food items using their Item IDs.
- **Quantity Selection:** Customers can choose the required quantity.
- **Input Validation:** Prevents invalid item IDs and quantities.
- **Automatic Billing:** Calculates the total amount based on selected items and quantities.
- **Checkout System:** Generates a final bill after completing the order.
- **User-Friendly Interface:** Simple menu-driven console interface.

## 🍟 Available Food Menu

| Item ID | Food Item | Price |
|---|---|---:|
| 1 | Veg Burger | ₹60 |
| 2 | French Fries | ₹50 |
| 3 | Cold Coffee | ₹70 |
| 4 | Veg Sandwich | ₹40 |

## 🛠️ Technologies Used

- **Programming Language:** C++
- **Concepts:** Object-Oriented Programming (OOP)
- **Header Files:** iostream, vector, string
- **Interface:** Console-Based Application
- **Compiler:** GCC / MinGW / Any C++ compatible compiler

## 🧠 OOP Concepts Implemented

This project demonstrates the following OOP concepts:

1. **Class and Objects:** Classes `MenuItem` and `Canteen` are used to organize the program.
2. **Encapsulation:** Data members such as item ID, name, and price are declared private and accessed using public getter methods.
3. **Constructors:** Constructors initialize food item details when objects are created.
4. **Data Abstraction:** Internal implementation details are hidden from the user.
5. **STL Vector:** Vectors are used to store menu items and customer cart details.
6. **Structures:** A `CartItem` structure stores the selected food item and its quantity.

## 📂 Project Structure

```text
Canteen-Management-System/
│
├── main.cpp
└── README.md
```

## ▶️ How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone YOUR_REPOSITORY_URL
```

**Step 2:** Open the project folder in VS Code.

**Step 3:** Compile the C++ program.

```bash
g++ main.cpp -o canteen
```

**Step 4:** Run the program.

For Windows:

```bash
canteen.exe
```

For Linux / macOS:

```bash
./canteen
```

## 💻 Sample Output

```text
=== Welcome to Canteen Management System ===

1. View Menu & Order
2. Exit

Enter your choice (1-2): 1

--- Canteen Menu ---
[1] Veg Burger - ₹60
[2] French Fries - ₹50
[3] Cold Coffee - ₹70
[4] Veg Sandwich - ₹40

Enter Item ID to order (or 0 to checkout): 1

Enter quantity for Veg Burger: 2

Added 2 x Veg Burger to your order.

Enter Item ID to order (or 0 to checkout): 3

Enter quantity for Cold Coffee: 1

Added 1 x Cold Coffee to your order.

Enter Item ID to order (or 0 to checkout): 0

================================
       YOUR CANTEEN BILL
================================
Veg Burger (x2) - ₹120
Cold Coffee (x1) - ₹70
--------------------------------
Total Amount: ₹190
================================
Thank you! Visit again.
```

## 🔮 Future Improvements

The project can be enhanced further by adding:

- Admin login system.
- Option to add, update, and delete food items.
- Customer details and order history.
- Discount and tax calculation.
- Payment options.
- File handling to save customer orders permanently.
- Graphical User Interface (GUI).

## 🎓
