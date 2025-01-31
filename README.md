# Login Authentication App
![hippo](https://github.com/user-attachments/assets/62358771-b33c-45a0-a274-8bbb1b5dfa4c)

This Python-based GUI application provides user authentication (sign-up and login) using Tkinter for the graphical interface and OpenPyXL for Excel file management.

## Features

- **User Signup:** Create a new account with a unique username and password.
- **User Login:** Access the application with existing credentials.
- **Error Handling:** Detects duplicate usernames during signup and incorrect credentials during login.
- **Simple GUI:** Interactive and user-friendly interface.

## Prerequisites

- **Python 3.x**
- Required library:
  ```bash
  pip install openpyxl
  ```
- **Directory Structure:**
  ```
  project_directory/
  ├─ files/
  │   ├─ signup.png (Signup page background)
  │   ├─ button.png (Signup button image)
  │   ├─ loginpage.png (Login page background)
  │   └─ login.png (Login button image)
  └─ users.xlsx (Excel file to store user credentials)
  ```

## How to Run

1. Clone or download the repository.
2. Ensure the `files/` directory contains the required image assets and the `users.xlsx` file.
3. Run the program:
   ```bash
   python app.py
   ```

## Usage

### **Signup Page**

1. Enter a unique username and password.
2. Click the signup button.
3. If the username already exists, a message will appear.

### **Login Page**

1. Enter your registered username and password.
2. Click the login button.
3. If the credentials are incorrect, appropriate messages will be shown.

## Notes

- Ensure `users.xlsx` exists with the correct structure:
  | Username | Password |
  | -------- | -------- |
- The program automatically appends new users during signup.
- Verify image dimensions and file paths if any UI issues occur.

## Credits

Developed by [Your Name] for educational purposes and practical demonstration of GUI-based applications.

Let me know if you'd like any adjustments or additional sections added to the README file!
