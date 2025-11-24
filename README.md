# LIBRARY-BOOKS
📚 Python Library Management System (LMS)

A simple and beginner-friendly Library Management System built in Python!
This program lets you display, issue, add, and return books using a text-file-based storage system.
Perfect for beginners to understand file handling, classes, and basic data structures. 😄

✨ Features

✅ Display all books with ID, title, and status
✅ Issue books to users using a unique ID
✅ Add new books to the library
✅ Return issued books
✅ Automatically updates the books file
✅ Simple console-based menu navigation

🛠️ How It Works

The project uses a .txt file to store book titles.
Each book in the library has:

Book ID

Title

Lender Name

Lend Date

Status (Available / Issued)

The LMS class handles all library operations:

display_books()

Issue_books()

add_books()

return_books()

update_file()

📦 File Structure
📁 Project Folder
 ├── list_of_books.txt   # Stores all book titles
 └── main.py             # Contains LMS class and program logic

▶️ How to Run

Make sure list_of_books.txt exists or let the script auto-create it.

Run the script:

python main.py


Choose options from the menu:

Press D To Display Books
Press I To Issue Books
Press A To Add Books
Press R To Return Books
Press Q To Quit

🧠 Code Overview

The heart of the system is the LMS class, which reads the books file, loads book data into a dictionary, and updates the file whenever a change happens.

Example Data Structure:
{
    "101": {
        "books_title": "Book Name",
        "lender_name": "",
        "lend_date": "",
        "status": "Available"
    }
}

📝 Notes

Books added must have titles less than 20 characters.

Issuing a book records the user name and date/time.

Returning a book resets its details to default.

🚀 Future Improvements (Optional)

✨ Add search functionality
✨ Add GUI (Tkinter / PyQt)
✨ Convert storage system to JSON or SQLite
✨ Add password-protected admin mode