# Python Calculator
    
## Description:
A python calculator that runs within the terminal. There are a variety of operations to choose from: add, subtract, multiply, divide, modulus (calculate remainder), and exponent (to work out a power of a number). 
    
Upon running the program, the user is greeted and is prompted to enter the first number. Then, a list of supported operations is displayed and the find_operation() function is called. This function will determine if the input is valid and return both the validity of the input (True / False) and the input itself. If False is returned, the value will be marked as 0 - as a placeholder. This function will repeatedly be called until the input is valid.

Next, the user is prompted for a second number, and applies the calculation to the first number.

An interesting design choice I decided to make, was the ability to continue calculating with the same number if the user chooses so. The program asks the user if they want to calculate with the same number, start with a new number, or exit the program. I find this very interesting as despite the logic being simple, it adds a whole new layer to the user experience. Should the user choose this, the output is stored and used as the new first number. The process repeats until the user opts to quit, escaping the while loop.

## Screenshot:
![Calculator](https://github.com/sethumadhavan505/GWING-INTERNSHIP-/blob/main/Testcase1.png)


# Currency Converter Python Project

## Description
Please you should run the program in a compatible environment like Google Colab, Python IDLE, VS Code, or Jupyter Notebook. A real-time Python project designed to use up-to-date exchange rates and offer quick and accurate conversions for a variety of different currencies. The program is built using Python and can be accessed via a user-friendly interface that allows users to easily select their desired currencies and enter the amount they wish to convert.

## Features
Real-time exchange rates
User-friendly interface
Support for a variety of currencies
Quick and accurate conversions

## Prerequisites
You need Python installed on your Computer
You must install required libraries like requests using pip install requests
You must have an active internet connection since the program fetches real-time currency rates.
You should run the program in a compatible environment like Google Colab, Python IDLE, VS Code, or Jupyter Notebook.
