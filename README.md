# 📚 Library Management System (C++)

![Made with C++](https://img.shields.io/badge/Made%20with-C++-blue?style=for-the-badge&logo=cplusplus)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Console-lightgrey?style=for-the-badge)

---

## 🔹 Project Overview
This is a beginner-friendly **Library Management System** built in **C++** using **Object-Oriented Programming (OOP)** concepts.  

It allows:
- **Admins** to add, view, and delete books  
- **Users** to search, borrow, and return books  
- Data is managed using **C++ STL containers** (`unordered_map`, `vector`, etc.)  

This project is **console-based** and is ideal for learning **C++ OOP + Data Structures**.

---

## 🔹 Features
✅ **Admin Features**
- Add books  
- Delete books  
- View all books  

✅ **User Features**
- Register new user  
- Borrow books  
- Return books  
- Search books by title  

✅ **Technical Highlights**
- **Language:** C++17  
- **OOP Concepts:** Classes, structs, encapsulation  
- **Data Structures Used:**  
  - `unordered_map` → store books & users  
  - `vector` → manage borrowed books list  
  - `optional` → safe retrieval of users  

---

## 🔹 File Structure
LibraryMS/
├── main.cpp # Entry point
├── Book.h/.cpp # Book struct
├── User.h/.cpp # User struct
├── Library.h/.cpp # Core library logic
├── Menu.h/.cpp # User/Admin menu system
├── Makefile # (optional) easy build
├── LICENSE # License file (MIT)
└── README.md # Project documentation

---

## 🔹 How to Run

### 1. Compile
```bash
g++ -std=c++17 -o library main.cpp Book.cpp User.cpp Library.cpp Menu.cpp
./library

-- Main Menu --
1. Admin
2. User
3. Exit

```
🔹 Example Workflow

Admin

Add Book → ID=101, Title="C++ Primer", Author="Lippman", Copies=3  

View Books → shows list with availability

User

Enter User ID=1, Name="Alice"

Borrow Book (ID=101) → Success

Return Book (ID=101) → Success

🔹 Installation (Optional Git Setup)

If using Git:
git clone https://github.com/<your-username>/LibraryMS.git
cd LibraryMS
g++ -std=c++17 -o library main.cpp Book.cpp User.cpp Library.cpp Menu.cpp
./library

