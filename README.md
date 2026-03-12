# Python File Manager (CLI)

A simple Command Line File Management System built using Python.
This project allows users to create, read, update, and delete files directly from the terminal. It was developed to practice Python fundamentals such as file handling, working with file paths, and basic program logic.

# Features
- Create a new file and write content into it
- Read the content of an existing file
- Update files by:
  - Renaming the file
  - Overwriting file content
  - Appending new content
- Delete files from the system
- Display available files and folders in the current directory
- Basic error handling for invalid inputs or missing files

# Technologies Used
- Python
- pathlib module for file path handling
- os module for file operations

# Concepts Practiced
This project helped strengthen understanding of:
- Python functions
- File handling (read, write, append)
- Working with file paths using pathlib
- Exception handling (try and except)
- Conditional statements
- User input handling

# Project Structure
```
python-file-manager
│
└── main.py
```
main.py contains the full logic for creating, reading, updating, and deleting files.

# How to Run the Project
1. Clone the repository
git clone https://github.com/IqraHasnain/python-file-manager.git

2. Navigate to the project folder
cd python-file-manager

3. Run the program
python main.py

4. Follow the instructions shown in the terminal.

# Example Menu
The program provides the following options:
1. Create File
2. Read File
3. Update File
4. Delete File
5. Exit
Users simply select an option and follow the prompts.

# Future Improvements
Possible improvements for this project include:
- Adding a continuous menu system
- Adding better input validation
- Logging file operations
- Converting the project into a graphical interface (GUI)

# Author
Created as a Python learning project to practice file handling and strengthen programming fundamentals.

# Demo (CLI Output)
```
Example of how the program runs in the terminal:

------ Python File Manager ------

1. Create File
2. Read File
3. Update File
4. Delete File
5. Exit

Enter your choice: 1
Enter file name: notes.txt
Enter content for the file: Python practice project

File created successfully.
```
