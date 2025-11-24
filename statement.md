# 📄 Project Statement — Library Management System (LMS)

## 📘 Overview
This project is a **Library Management System (LMS)** developed in Python.  
It provides a simple, menu-driven interface that allows users to manage books in a library using basic file handling and object-oriented programming concepts.

The system uses a text file (`list_of_books.txt`) to store book titles and maintains a Python dictionary to track each book’s:
- Unique Book ID  
- Title  
- Lending Status  
- Lender Name  
- Lend Date  

---

## 🎯 Project Objective
The objective of this project is to design a lightweight and efficient system that allows:
- Displaying all books with their availability status  
- Issuing books to users with automatic timestamp recording  
- Adding new books to the library database  
- Returning issued books and updating the records  
- Maintaining data persistence using external file storage  

This project serves as an excellent learning tool for understanding:
- Python classes & object-oriented programming  
- File I/O operations  
- Dictionaries and data manipulation  
- Input handling and validation  
- System flow control  

---

## 🛠️ System Features
### 1. **Display Books**
Shows a complete list of books along with their unique ID and availability status.

### 2. **Issue Books**
Allows a user to borrow a book by entering its ID.  
The system records:
- Lender's name  
- Issue date and time  
It prevents issuing a book that is already issued to someone else.

### 3. **Add Books**
Adds a new book to both:
- The text file  
- The internal dictionary  
Validates title length and prevents empty inputs.

### 4. **Return Books**
Marks a previously issued book as “Available” and resets its lender details.

### 5. **Persistent Data Storage**
All book updates are written back to the text file to preserve data between sessions.

---

## 🧩 System Flow
1. User runs the program.  
2. The LMS class loads the books from the text file.  
3. A menu is shown with options:
   - Display Books  
   - Issue Books  
   - Add Books  
   - Return Books  
   - Quit  
4. Based on user input, the corresponding method executes.  
5. Data is updated in real-time and saved persistently.

---

## 📂 File Used
**`list_of_books.txt`**  
Stores book titles—one title per line.  
If the file does not exist, the program automatically creates it.

---

## 👨‍💻 Technology Used
- **Python 3.x**
- Concepts:
  - Object-Oriented Programming
  - File Handling
  - Dictionaries
  - Exception Handling
  - User Input Handling

---

## 📌 Conclusion
This Library Management System is a beginner-friendly yet functional console-based application.  
It demonstrates practical use of Python fundamentals and offers a strong foundation for expanding into more advanced management systems, including GUI-based or database-driven versions.