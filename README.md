CS50 Python – Lines of Code

This project is part of Harvard University’s CS50: Introduction to Programming with Python.

Description

This program counts the number of lines of actual code in a Python file.
It excludes:

Blank lines

Lines containing only comments

The program is run from the command line and requires exactly one argument: the name of a Python file.

How It Works

The program checks that exactly one command-line argument is provided.

It verifies that the argument refers to a file with a .py extension.

If the file does not exist, the program exits with an error message.

The file is read line by line.

Lines that are blank or begin with # are ignored.

All other lines are counted as lines of code.

The final count is printed to the terminal.

How to Run

Make sure you have Python 3 installed.

From the terminal:

python lines.py filename.py


Example:

python lines.py hello.py


Output:

5

Error Handling

The program exits with an appropriate message in the following cases:

No command-line argument provided

More than one command-line argument provided

File is not a Python file

File does not exist

Concepts Used

Command-line arguments (sys.argv)

File handling

Exception handling

String methods

Loops and conditionals
