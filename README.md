# Claculator.c

# C Calculator Program

# About the Project

This project is a simple menu-driven calculator developed using the C programming language. It performs basic arithmetic operations and allows users to view their previous calculations.

The project was created as a programming practice project to understand the use of structures, loops, conditional statements, functions of the standard input/output library, and switch-case statements in C.

# Features

* Addition of two numbers
* Subtraction of two numbers
* Multiplication of two numbers
* Division of two numbers
* Calculation history
* Input validation for menu choices and numbers
* Error handling for division by zero
* Simple menu-driven interface

## Technologies Used

* **Programming Language:** C
* **Header File:** `stdio.h`
* **Compiler:** GCC or any compatible C compiler
* **Editor:** Visual Studio Code

## Project Structure

```text
program-calculator/
│
├── program-calculator.c
└── README.md
```

## How to Run the Program

### Step 1: Download the Project

Clone this repository or download the source code to your computer.

### Step 2: Open the Project

Open the project folder in Visual Studio Code or another C-compatible editor.

### Step 3: Compile the Code

If GCC is installed, open the terminal and run:

```bash
gcc program-calculator.c -o calculator
```

### Step 4: Run the Program

**On Windows:**

```bash
.\calculator.exe
```

**On Linux:**

```bash
./calculator
```

## How It Works

When the program starts, it displays a menu containing six options. The user selects an arithmetic operation and enters two numbers.

The program calculates and displays the result. Each successful calculation is stored in an array of structures, allowing the user to view the calculation history later.

The program also checks for invalid input and prevents division by zero.

## Sample Output

```text
========== CALCULATOR ==========
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Show Calculation History
6. Exit
================================

Enter your choice: 1
Enter first number: 20
Enter second number: 10
Result: 30.00

========== CALCULATOR ==========
1. Addition
2. Subtraction
3. Multiplication
4. Division
5. Show Calculation History
6. Exit
================================

Enter your choice: 5

======= CALCULATION HISTORY =======
1. 20.00 + 10.00 = 30.00
```

*Note: This is an illustrative sample output.*

## Concepts Used

This project demonstrates several fundamental concepts of C programming:

* Structures (`struct`)
* Arrays
* Variables and data types
* `do-while` loop
* `if-else` statements
* `switch-case` statement
* User input using `scanf()`
* Output using `printf()`
* Basic input validation
* Arithmetic operators

## Limitations

* The program supports only basic arithmetic operations.
* The calculation history is stored temporarily in memory and is lost when the program exits.
* The history can store up to 100 successful calculations.

## Future Improvements

* Add more mathematical operations.
* Save calculation history to a file.
* Improve input handling.
* Add a graphical user interface.

## Conclusion

This project provides practical experience with basic C programming concepts. It demonstrates how a menu-driven application can perform calculations, handle common input errors, and maintain a history of operations using structures and arrays.

## Author

**Sanjiv Kumar**

## License

This project is available for educational and learning purposes.

