# Login Application
This is a simple GUI-based login application built using Python's Tkinter library. The application prompts users to enter a username and password, and validates the credentials.

## Features
- Input fields for username and password.
- Basic validation for empty fields.
- Displays message boxes for successful login or incorrect credentials.

## Prerequisites
- Python 3.x
- Tkinter library (usually included with Python installations)

## Usage
Run the following command to start the application:
```bash
python login.py

## Code Breakdown
Imports:

from tkinter import *: Imports all necessary Tkinter components.
from tkinter import messagebox: Imports the messagebox module for displaying messages.
login Function:

Retrieves the username and password entered by the user.
Validates the input and displays appropriate messages using messagebox.showinfo.
Main Application:

Initializes the Tkinter window.
Creates labels, entry fields, and a login button.
Sets up the layout using the place method.
Starts the Tkinter event loop with root.mainloop().
