# Python GUI Calculator

A simple calculator application built with Python’s Tkinter library. This calculator supports basic arithmetic operations (addition, subtraction, multiplication, division) and has a clean, user-friendly interface.

## Features

- Perform basic arithmetic: +, -, *, /
- Supports floating-point numbers
- Clear button to reset calculations
- Error handling for syntax mistakes and division by zero
- Responsive GUI with buttons for each digit and operator

## How It Works

The application uses:
- **Tkinter** for the graphical user interface.
- **Label** widget to display the equation/result.
- **Buttons** arranged in a grid for digits (0-9) and operators.
- A **Frame** to organize the buttons.
- A global variable `equation_text` stores the current equation.
- `button_press(num)` updates the equation with each button press.
- `equals()` evaluates the equation using Python’s `eval()` function and updates the display.
- `clear()` resets the equation.

## Files

- `calculator.py`: The main script containing the calculator implementation.

## How to Run

1. Make sure you have **Python 3** installed.
2. Download this script or clone the repository.
3. Open a terminal in the project directory.
4. Run the program:
   ```bash
   python main.py
5. A window will open displaying the calculator interface.

Dependencies
This program uses only Python’s built-in Tkinter library — no external packages required.

Usage
Click number buttons (0-9) and operators (+, -, *, /) to build your equation.

Press = to calculate the result.

Press clear to reset the calculator.

Error Handling
Displays "syntax error" for invalid inputs.

Displays "arithmetic error" for division by zero.

Customization
You can change:

Window size in window.geometry("500x500").

Button dimensions by adjusting height and width in Button widgets.

Fonts by modifying the font parameter in Label and Button.
