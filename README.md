# Simple Calculator

This project is a simple calculator built using HTML, CSS, and JavaScript. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator also supports keyboard input for a more convenient user experience.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [JavaScript Functionality](#javascript-functionality)
- [Enhancements](#enhancements)
- [Acknowledgments](#acknowledgments)
- [License](#license)
- [Contact](#contact)

## Features

- Basic arithmetic operations: addition, subtraction, multiplication, and division.
- Clear and easy-to-use interface.
- Responsive design that works on various screen sizes.
- Keyboard support for input.

## Technologies Used

- HTML5
- CSS3
- JavaScript

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/DellahM/Simple-Calculator.git

2.Navigate to the project directory:


Open the index.html file in your web browser to view the calculator.

Usage
Basic Operations:

Click on the number buttons (0-9) to input numbers.
Use the operation buttons (+, -, x, /, %) to select the operation you want to perform.
Click the = button to calculate the result.
Clearing Input:

Click the C button to clear all inputs.
Click the CE button to clear the last input.
Decimal Input:

Use the . button to input decimal numbers.
Keyboard Input:

You can also use your keyboard to input numbers and operations:
Number keys (0-9) and the decimal point (.) for input.
Operation keys (+, -, /, %) for selecting operations.
Press Enter or = to calculate the result.
JavaScript Functionality
The calculator's functionality is implemented in JavaScript. Here’s a brief overview of how it works:

Variables:

display1El, display2El, and tempResultEl are used to reference the display elements.
numbersEl and operationEl are NodeLists of number and operation buttons, respectively.
dis1Num, dis2Num, and result store the current input and result values.
lastOperation keeps track of the last operation performed.
haveDot is a flag to prevent multiple decimal points in a number.
Event Listeners:

Each number button has an event listener that updates the display when clicked.
Each operation button has an event listener that performs the selected operation when clicked.
The equal button calculates the result and updates the display.
The clear buttons reset the calculator or clear the last input.
Keyboard Support:

The calculator listens for keyboard events to allow input via the keyboard.
Functions like clickButtonEl, clickOperation, and clickEqual simulate button clicks based on keyboard input.
Example JavaScript Code
Here’s a snippet of the JavaScript code that handles the calculator's functionality:



\\\\const display1El = document.querySelector(".display-1");
const display2El = document.querySelector(".display-2");
const tempResultEl = document.querySelector(".temp-result");
const numbersEl = document.querySelectorAll(".number");
const operationEl = document.querySelectorAll(".operation");
const equalEl = document.querySelector(".equal");
const clearAllEl = document.querySelector(".all-clear");
const clearLastEl = document.querySelector(".last-entity-clear");

let dis1Num = "";
let dis2Num = "";
let result = null;
let lastOperation = "";
let haveDot = false;

// Event listeners for number buttons
numbersEl.forEach((number) => {
    number.addEventListener("click", (e) => {
        // Handle number input
    });
});

// Event listeners for operation buttons
operationEl.forEach((operation) => {
    operation.addEventListener("click", (e) => {
        // Handle operation input
    });
});

// Function to perform calculations
function mathOperation() {
    // Perform the selected operation
}

// Event listener for equal button
equalEl.addEventListener("click", () => {
    // Calculate and display the result
});

// Event listeners for clear buttons
clearAllEl.addEventListener("click", () => {
    // Clear all inputs
});

clearLastEl.addEventListener("click", () => {
    // Clear last input
});

// Keyboard support
window.addEventListener("keydown", (e) => {
    // Handle keyboard input
});\\\\\\\








   Enhancements
While the current calculator is functional, there are several potential enhancements that could improve its usability and features:

Advanced Operations:

Implement additional mathematical functions such as square root, exponentiation, and trigonometric functions.
History Feature:

Add a history log to display previous calculations and results.
Memory Functions:

Implement memory functions (M+, M-, MR, MC) to store and recall values.
Theming:

Allow users to switch between different themes (light/dark mode) for better accessibility.
Error Handling:

Improve error handling for invalid operations (e.g., division by zero) and provide user feedback.
Unit Testing:

Write unit tests for the JavaScript functions to ensure reliability and correctness.
Acknowledgments
Inspiration: This project was inspired by various online calculator applications and tutorials.
Libraries: The project uses standard web technologies (HTML, CSS, JavaScript) without any external libraries, making it lightweight and easy to understand.
Fonts: The project uses the "Montserrat" font for a modern look, which can be easily changed by modifying the CSS.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any inquiries or feedback, feel free to reach out:

Email: dellahmiheso@gmail.com
GitHub: DellahM



Thank you for checking out the Simple Calculator project! We hope it helps you with basic arithmetic calculations. If you have any questions, suggestions, or need assistance, feel free to reach out or contribute to the project.



