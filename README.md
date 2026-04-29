# Pharmacy-Manager
Repository for https://replit.com/@haritalluri/Pharmacy-Manager


# 💊 Pharmacy Management System

![C++](https://img.shields.io/badge/Language-C%2B%2B-blue?style=for-the-badge&logo=cplusplus)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-lightgrey?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-Academic-orange?style=for-the-badge)

> A console-based Pharmacy Management System built in **C++** as a Bachelor's degree final project. It automates medicine order processing, receipt generation, order modification, and daily sales reporting using linked list data structures.

---

## 📋 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Medicine Inventory](#medicine-inventory)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Author](#author)

---

## 📖 About the Project

The **Pharmacy Management System (PMS)** is designed to computerize the front office operations of a pharmacy. It eliminates manual errors by providing a fast, user-friendly, and cost-effective digital solution for managing medicine orders and customer records.

The system handles:
- Customer order placement
- Receipt generation and payment processing
- Order modification and deletion
- Daily sales summary reports

---

## ✨ Features

| Feature | Description |
|---|---|
| 🛒 **Take New Order** | Add a new medicine order with customer details |
| 🗑️ **Delete Order** | Remove any existing order by receipt number |
| ✏️ **Modify Order** | Edit an existing order's details and medicines |
| 🧾 **Print Receipt & Pay** | View itemized bill and process payment |
| 📊 **Daily Summary** | View all orders and total sales for the day |
| 🚪 **Exit** | Safely exit the application |

---

## 💊 Medicine Inventory

| Drug ID | Drug Type | Medicine Name | Price |
|---|---|---|---|
| 0001 | OTC | Probiotics | Rs 2.00 |
| 0002 | OTC | Vitamin C (500mg) | Rs 3.00 |
| 0003 | OTC | Acid Free C (500mg) | Rs 1.00 |
| 0004 | OTC | Women's Multivate | Rs 4.00 |
| 0005 | OTC | Marino Tablet | Rs 1.00 |
| 0006 | OTC | Maxi Cal Tablet | Rs 5.00 |
| 0007 | OTC | Amino Zinc Tablet | Rs 7.00 |
| 0008 | OTC | Burnex | Rs 4.00 |
| 0009 | OTC | Fabuloss 5 | Rs 3.00 |
| 0010 | OTC | Royal Propollen | Rs 5.00 |

---

## 🛠️ Tech Stack

- **Language:** C++
- **Concepts Used:**
  - Object-Oriented Programming (OOP)
  - Linked Lists (Dynamic Memory Allocation)
  - Structs and Classes
  - File I/O (fstream)
  - Console UI Design

---

## 🚀 Getting Started

### Prerequisites

Make sure you have a C++ compiler installed:

- **Windows:** [MinGW / g++](https://www.mingw-w64.org/) or Visual Studio
- **Mac:** `xcode-select --install`
- **Linux:** `sudo apt install g++`

### Clone the Repository

```bash
git clone https://github.com/your-username/pharmacy-management-system.git
cd pharmacy-management-system
```

---

## ▶️ How to Run

### Compile

```bash
g++ pharmacy_management.cpp -o pharmacy
```

### Run

```bash
# Windows
pharmacy.exe

# Linux / Mac
./pharmacy
```

### Or Run Online (No Installation Needed)

1. Go to 👉 [https://www.onlinegdb.com](https://www.onlinegdb.com)
2. Select **C++** as the language
3. Paste the source code
4. Click **Run ▶️**

---

## 📁 Project Structure

```
pharmacy-management-system/
│
├── pharmacy_management.cpp   # Main source code
├── README.md                 # Project documentation
└── .replit                   # Replit configuration (if using Replit)
```

---

## 📸 Screenshots

### Main Menu
```
          APOLLO Pharmacy
          JKC Nagar
  ================================================

  --------------------------------------------------
  ||   1. Take new Medicine order            ||
  ||   2. Delete latest Medicine order       ||
  ||   3. Modify Order List                  ||
  ||   4. Print the Reciept and Make Payment ||
  ||   5. Daily Summary of total Sale        ||
  ||   6. Exit                               ||
  --------------------------------------------------
```

---

## 👩‍💻 Author

**Haritalluri**
- 🎓 Bachelor's Degree Project
- 💻 Built with C++ | Data Structures | OOP

---

## 📝 License

This project was developed as an **academic project** for Bachelor's degree requirements.  
Feel free to use it for learning and reference purposes.

---

> ⭐ If you found this project helpful, please give it a **star** on GitHub!
