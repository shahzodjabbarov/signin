Login Authentication App
![new](https://github.com/user-attachments/assets/7a272e64-9775-482f-bb3f-52745d7db6db)
This Python-based GUI application provides user authentication (sign-up and login) using Tkinter for the graphical interface and OpenPyXL for Excel file management.


Features

User Signup: Create a new account with a unique username and password.

User Login: Access the application with existing credentials.

Error Handling: Detects duplicate usernames during signup and incorrect credentials during login.

Simple GUI: Interactive and user-friendly interface.

Prerequisites

Python 3.x

Required library:

pip install openpyxl

Directory Structure:

project_directory/
├─ files/
│   ├─ signup.png (Signup page background)
│   ├─ button.png (Signup button image)
│   ├─ loginpage.png (Login page background)
│   └─ login.png (Login button image)
└─ users.xlsx (Excel file to store user credentials)

How to Run

Clone or download the repository.

Ensure the files/ directory contains the required image assets and the users.xlsx file.

Run the program:

python app.py

Usage

Signup Page

Enter a unique username and password.

Click the signup button.

If the username already exists, a message will appear.

Login Page

Enter your registered username and password.

Click the login button.

If the credentials are incorrect, appropriate messages will be shown.

Notes

Ensure users.xlsx exists with the correct structure:

Username

Password

The program automatically appends new users during signup.

Verify image dimensions and file paths if any UI issues occur.
