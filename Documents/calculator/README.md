
Python Calculator Project: Applied Knowledge Documentation


Project Snapshot

This is a command-line calculator application built with Python 3. It was developed primarily as a hands-on exercise to apply foundational programming concepts. The application correctly handles the four main arithmetic operations: Addition, Subtraction, Multiplication, and Division.


Lessons Applied: Technical Decisions and Rationale

The final code structure reflects several best practices and technical decisions learned during the coursework:
1. Functional Decomposition: Instead of writing one long block of code, I separated the logic into distinct functions (add, subtract, multiply, divide).
    * Applied Knowledge: This makes the code modular and much easier to debug. If the subtraction logic breaks, I only check the subtract() function, not the whole script.
2. Continuous Flow Control: The entire program runs inside a while True loop, managed by the calculator() function.
    * Applied Knowledge: This design ensures the user can perform multiple calculations efficiently without the inconvenience of restarting the script every time.
3. Robust Error Handling (Input and Math):
    * A try...except block is used to manage user input. Lesson Learned: Users don't always follow instructions. The try...except block stops the program from crashing if a user types a letter instead of a number, which is essential for stable applications.
    * The division function specifically checks for a denominator of zero (if y == 0). Lesson Learned: Anticipating exceptions like ZeroDivisionError is necessary for writing reliable code.
4. Clear Entry Point: The script uses the standard if __name__ == "__main__": block.
    * Applied Knowledge: This ensures the main calculator() function is only run when the file is executed directly, which is the industry standard for starting a Python application.


Key Learning Points (The Development Process)

The most valuable lessons during the development cycle were related to environment and tooling:
1. File Path and Naming are Critical: The project demonstrated the importance of case-sensitivity (e.g., Calculator vs. calculator) and ensuring the file being referenced (calculator.py) actually exists in the current working directory of the terminal. Misnaming or misplacing files leads directly to [Errno 2] No such file or directory errors.
2. Mastering Git Workflow: I learned the exact sequence of commands needed to move a local project onto GitHub:
    * git init (Start tracking changes).
    * git add [filename] (Stage the exact file).
    * git commit -m "Message" (Create a snapshot).
    * git push -u origin master (Connect and upload the committed code).
3. Debugging by Isolation: The solution to persistent errors (like the SyntaxError or file-not-found issues) was always to isolate the problem (check the case, check the path) rather than changing large sections of code.



Python Calculator Project: Applied Knowledge Documentation


Project Snapshot

This is a command-line calculator application built with Python 3. It was developed primarily as a hands-on exercise to apply foundational programming concepts. The application correctly handles the four main arithmetic operations: Addition, Subtraction, Multiplication, and Division.


Lessons Applied: Technical Decisions and Rationale

The final code structure reflects several best practices and technical decisions learned during the coursework:
1. Functional Decomposition: Instead of writing one long block of code, I separated the logic into distinct functions (add, subtract, multiply, divide).
    * Applied Knowledge: This makes the code modular and much easier to debug. If the subtraction logic breaks, I only check the subtract() function, not the whole script.
2. Continuous Flow Control: The entire program runs inside a while True loop, managed by the calculator() function.
    * Applied Knowledge: This design ensures the user can perform multiple calculations efficiently without the inconvenience of restarting the script every time.
3. Robust Error Handling (Input and Math):
    * A try...except block is used to manage user input. Lesson Learned: Users don't always follow instructions. The try...except block stops the program from crashing if a user types a letter instead of a number, which is essential for stable applications.
    * The division function specifically checks for a denominator of zero (if y == 0). Lesson Learned: Anticipating exceptions like ZeroDivisionError is necessary for writing reliable code.
4. Clear Entry Point: The script uses the standard if __name__ == "__main__": block.
    * Applied Knowledge: This ensures the main calculator() function is only run when the file is executed directly, which is the industry standard for starting a Python application.


Key Learning Points (The Development Process)

The most valuable lessons during the development cycle were related to environment and tooling:
1. File Path and Naming are Critical: The project demonstrated the importance of case-sensitivity (e.g., Calculator vs. calculator) and ensuring the file being referenced (calculator.py) actually exists in the current working directory of the terminal. Misnaming or misplacing files leads directly to [Errno 2] No such file or directory errors.
2. Mastering Git Workflow: I learned the exact sequence of commands needed to move a local project onto GitHub:
    * git init (Start tracking changes).
    * git add [filename] (Stage the exact file).
    * git commit -m "Message" (Create a snapshot).
    * git push -u origin master (Connect and upload the committed code).
3. Debugging by Isolation: The solution to persistent errors (like the SyntaxError or file-not-found issues) was always to isolate the problem (check the case, check the path) rather than changing large sections of code.


Execution Guide


Requirements

Python 3 must be installed on the machine.

Running the Application

1. Change Directory: Navigate to the project folder in your terminal:cd ~/Documents/calculator
2. Execute the Script: Launch the calculator using the command that successfully executed the file:python Calculator
3. Interaction: Use the menu options (1, 2, 3, 4) to select operations. The program will loop until the user chooses to exit.
