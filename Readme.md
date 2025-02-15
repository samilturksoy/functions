# Functions

## Overview
This project contains various JavaScript functions demonstrating different programming concepts such as function declarations, expressions, arrow functions, and default parameters.

## Functions

### sayHello
- **Description**: Greets the user with a message.
- **Parameters**: 
  - `name` (string): The name of the user.
- **Example**:
  ```javascript
  console.log(sayHello("Alice")); // Output: Merhaba, Alice!
  ```

### multiply
- **Description**: Multiplies two numbers.
- **Parameters**: 
  - `num1` (number): The first number.
  - `num2` (number): The second number.
- **Example**:
  ```javascript
  console.log(multiply(5, 3)); // Output: 15
  ```

### divide
- **Description**: Divides the first number by the second.
- **Parameters**: 
  - `num1` (number): The numerator.
  - `num2` (number): The denominator.
- **Example**:
  ```javascript
  console.log(divide(10, 2)); // Output: 5
  ```

### greetUser
- **Description**: Greets the user with an optional surname.
- **Parameters**: 
  - `name` (string, optional): The first name of the user. Defaults to "Misafir".
  - `surname` (string, optional): The surname of the user.
- **Example**:
  ```javascript
  console.log(greetUser()); // Output: Hoş geldin, Misafir!
  console.log(greetUser("John", "Doe")); // Output: Hoş geldin, John Doe!
  ```