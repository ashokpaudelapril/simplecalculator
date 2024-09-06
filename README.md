# Simple Web Calculator

This is a basic web-based calculator built using **HTML**, **CSS**, and **JavaScript**. The calculator supports basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features
- Addition, subtraction, multiplication, and division.
- Clear (C) button to reset the display.
- Delete (DEL) button to remove the last entered digit/operator.
- Responsive and clean design.

## Files

- `index.html`: The main HTML file that includes the structure of the calculator.
- `style.css`: The CSS file for styling the calculator interface.
- `script.js`: The JavaScript file that provides the functionality of the calculator (handling user inputs, calculations, etc.).

## Getting Started

1. **Clone or download the repository**:
    ```
    git clone https://github.com/your-username/simple-web-calculator.git
    ```
    Or download the zip file and extract it.

2. **Open the project**:
    - Open `index.html` in your web browser.

## How to Use

1. **Enter numbers**: Click on the number buttons to input numbers.
2. **Perform operations**: Use the `+`, `-`, `*`, `/` buttons to perform arithmetic operations.
3. **Clear display**: Use the `C` button to clear the calculator's display.
4. **Delete last digit/operator**: Use the `DEL` button to delete the last input.
5. **Calculate result**: After entering an expression, press the `=` button to calculate the result.

## Code Breakdown

### HTML (`index.html`)
The HTML file defines the structure of the calculator, including the display and buttons.

### CSS (`style.css`)
The CSS file adds style to the calculator, making it look modern and responsive.

### JavaScript (`script.js`)
The JavaScript file provides interactivity to the calculator. It handles number and operator inputs, clears the display, deletes the last character, and evaluates the entered expressions using `eval()`.

## Example Expression
5 + 3 * 2 = 11
- Click `5`, then `+`, then `3`, then `*`, then `2`, and finally press `=` to get `11`.

## Notes

- Be cautious when using the `eval()` function in JavaScript, as it can execute arbitrary code. For a simple calculator, it works well, but avoid using it in more complex or security-sensitive applications.

## License

This project is open-source and available under the MIT License.
