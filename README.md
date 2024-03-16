# DicePal

DicePal is a Java program that provides various functionalities for dice games and numeric operations. It offers a virtual craps game, a Pentagonal Number Generator, a Palindrome Checker, a Unit Converter, and a Password Validator. It caters to both recreational gaming and mathematical analysis needs.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Imports](#Imports)
- [Rating: 5/10](#Rating)

# About

DicePal is a Java program that provides various functionalities related to dice games and numeric operations. It offers a virtual craps game, a Pentagonal Number Generator, a Palindrome Checker, a Unit Converter, and a Password Validator. The program simulates dice rolls and determines outcomes based on game rules. It also helps in numeric analysis and problem-solving by checking if a number is a palindrome. DicePal caters to both recreational gaming and mathematical analysis needs.

# Features

DicePal is a versatile Java program that offers a virtual craps game, Pentagonal Number Generator, Palindrome Checker, Unit Converter, Password Validator, and Recreational Gaming and Mathematical Analysis. It allows players to roll dice, place bets, and experience the thrill of the casino without leaving their computer. Pentagonal numbers have fascinating properties, making them suitable for mathematical exploration or artistic inspiration. DicePal also checks if a given number is a palindrome, ensuring accuracy in analyzing phone numbers, dates, and secret codes. The program simplifies conversions between different units, such as kilometers to miles or Celsius to Fahrenheit. Additionally, DicePal validates passwords, ensuring security and allowing users to input their passwords. DicePal caters to both recreational gamers and mathematical analysts, offering a variety of features for both fun and analysis.

# Imports

Random, Scanner, random

# Rating

The evaluation of the project reveals several issues with code organization and readability, including inconsistent naming conventions, misspelled class names, indentation, and formatting. The program also lacks clear explanations for methods and classes, confusing variable names, and inconsistent capitalization in method names.
Functionality and completeness are good, with functions like generating pentagonal numbers, checking for palindromes, converting units, and checking passwords. However, some methods like `isValidPassword` have logical errors and are not complete. The functionality of printing meters and feet in a loop is also present.
Error handling is normal, with no handling for incorrect user input, empty or null passwords, potential divide by zero errors, or number format exceptions in the `isPalindrome` method. Efficiency could be improved in areas like redundant logic in the craps game methods, an inefficient loop in the `isValidPassword` method, no reuse of the `Random` instance in the `CrapsGame` class, and redundant calculations in the `footToMeter` and `meterToFoot` methods.
Overall, the project shows potential but requires significant improvements in various aspects to make it more robust and maintainable. Refactoring the code, addressing logical errors, and adding error handling would greatly enhance the project's quality.
