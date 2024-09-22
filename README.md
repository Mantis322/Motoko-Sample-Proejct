# Actor Calculator

A simple asynchronous calculator implemented in the Actor model.

## Features

- **Addition**: Adds a given integer to the current value.
- **Subtraction**: Subtracts a given integer from the current value.
- **Multiplication**: Multiplies the current value by a given integer.
- **Division**: Divides the current value by a given integer (returns `null` if divided by zero).
- **Clear**: Resets the current value to zero.

## Usage

### Methods

- `toplama(s: Int): async Int`
  - Adds `s` to the current value.
  
- `cikarma(s: Int): async Int`
  - Subtracts `s` from the current value.
  
- `carpma(s: Int): async Int`
  - Multiplies the current value by `s`.
  
- `bolme(s: Int): async ?Int`
  - Divides the current value by `s`. Returns `null` if `s` is 0.
  
- `temizle(): async ()`
  - Resets the current value to 0.
