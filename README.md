# Fibonacci Calculator with Algarodham Constraint

## Introduction
This project is a simple web application that calculates Fibonacci numbers with the Algarodham constraint. The Algarodham constraint restricts the Fibonacci numbers to be within the range of 0 to 1000.

## Usage
To find the 9th Fibonacci number with the Algarodham constraint, follow these steps:

1. Start from the base cases:
    - F(0) = 0
    - F(1) = 1

2. Use the recursive formula to find subsequent Fibonacci numbers:
    - F(2) = F(1) + F(0) = 1 + 0 = 1
    - F(3) = F(2) + F(1) = 1 + 1 = 2
    - F(4) = F(3) + F(2) = 2 + 1 = 3
    - F(5) = F(4) + F(3) = 3 + 2 = 5
    - F(6) = F(5) + F(4) = 5 + 3 = 8
    - F(7) = F(6) + F(5) = 8 + 5 = 13
    - F(8) = F(7) + F(6) = 13 + 8 = 21
    - F(9) = F(8) + F(7) = 21 + 13 = 34

So, the 9th Fibonacci number with the Algarodham constraint is 34.

## Dependencies
This project has no external dependencies. It uses HTML, CSS, and JavaScript for the user interface and calculation logic.

## Running the Application
To run the Fibonacci Calculator, simply open the `index.html` file in a web browser. Then, enter the desired position in the Fibonacci sequence and click the "Calculate" button.

## Contributors
- [Omor Faruk]
- [of.webdev@gmail.com]

## License
This project is licensed under the [MIT License](LICENSE).
