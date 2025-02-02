# Basic Java Input Methods

This repository demonstrates various techniques for handling user input in Java. It includes examples using multiple input methods such as:

- **Scanner**
- **BufferedReader**
- **DataInputStream**
- **Console**

Additionally, the repository features a simple factorial calculation to showcase how input data can be processed and used in computations.

## Repository Structure

- **InputProcessor.java**  
  Contains utility methods to:
  - Read input using different methods.
  - Calculate the factorial of a given number.

- **InputMain.java**  
  The main entry point of the application that:
  - Allows users to choose the input method.
  - Supports command-line argument input for quick calculations.
  - Demonstrates handling of user choices and input processing.

## How It Works

1. **Command-Line Argument**  
   If a command-line argument is provided, the program parses it as an integer and computes its factorial.

2. **Interactive Menu**  
   If no command-line argument is given, the user is presented with a menu to select one of the input methods. Once a choice is made, the corresponding method is used to capture an integer, and its factorial is computed and displayed.

## Running the Application

1. **Compile the Java Files**:
   ```bash
   javac InputProcessor.java InputMain.java
2. **Run with Command Line(Alternate/Optional)**
   ```bash
   java InputMain

## Purpose

This project is ideal for beginners who are looking to understand and compare different ways to read user input in Java. It also serves as a practical example for integrating input methods with simple computation logic.
