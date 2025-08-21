📚 Library Management System (C Project)
A simple Library Management System in C built for academic learning and practice.
This project demonstrates file handling, structures, menu-driven programming, and user authentication.
The system allows students to search, borrow, and return books, while admins can manage the library database and track transactions.
  
  ✨ Features
👨‍🎓 Student
Login with Student ID
View all available books
Search books by title
Borrow and return books
Transactions automatically logged

🛠️ Admin
Secure login with password (admin123)
Add new books to library
Delete books
Update book details
View all student transactions

📝 Tracking
Every borrow/return is logged in Transactions.txt with:
Student ID
Action (BORROW/RETURN)
Book ID, Title, Author
Timestamp

⚙️ Tech Details
Language: C
Data Storage: Books.txt (for book data), Transactions.txt (for logs)
Concepts Used:
File Handling (fopen, fscanf, fprintf)
Structures (struct Book)
String Handling (strcpy, strstr, etc.)
Menu-driven loops (switch, while)

To run:-
# Compile
gcc menu.c -o lms

📌 Future Enhancements
Borrow limit per student
Fine calculation for late returns
Store data in binary files or a SQL database
GUI/Website interface

