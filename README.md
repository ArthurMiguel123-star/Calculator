# Calculator

A simple calculator web application built using HTML, CSS, and JavaScript.

## Installation

To use the calculator, simply open the `index.html` file in a web browser. No additional installation is required.

## Usage

The calculator provides the following functionality:

- Basic arithmetic operations: addition, subtraction, multiplication, and division.
- Clear the current value with the "C" button.
- Delete the last digit with the "←" button.
- Perform the current operation and display the result with the "=" button.

Here's an example of how to use the calculator:

1. Enter a number using the numeric buttons.
2. Select an operation (e.g., `+`, `-`, `×`, `÷`) to perform on the current value.
3. Enter another number.
4. Press the "=" button to perform the operation and display the result.

```html
<div class="wrapper">
  <section class="screen">
    0
  </section>

  <section class="calc-buttons">
    <div class="calc-button-row">
      <button class="calc-button double">C</button>
      <button class="calc-button">←</button>
      <button class="calc-button">÷</button>
    </div>

    <!-- Additional button rows -->
  </section>
</div>
```

## API

The calculator's functionality is implemented in the `script.js` file. The main functions are:

- `buttonClick(value)`: Handles the click event for each button, dispatching the appropriate function based on the button's value.
- `handleSymbol(symbol)`: Handles the behavior of special buttons like "C", "=", and the operation symbols.
- `handleMath(symbol)`: Performs the requested mathematical operation.
- `flushOperation(intBuffer)`: Executes the current operation and updates the running total.
- `handleNumber(numberString)`: Handles the input of numeric values.
- `init()`: Sets up the event listener for the calculator buttons.

## Contributing

Contributions to the calculator project are welcome. If you find any issues or have suggestions for improvements, please feel free to open a new issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Testing

To test the calculator's functionality, you can open the `index.html` file in a web browser and interact with the calculator's buttons. Verify that the calculator performs the expected operations and displays the correct results.
