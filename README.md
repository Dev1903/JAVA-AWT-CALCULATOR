# Java Calculator Application (AWT)

This project is a simple calculator application built using Java's Abstract Window Toolkit (AWT) for the graphical user interface (GUI). It supports basic arithmetic operations such as addition, subtraction, multiplication, and division. The calculator dynamically updates the display based on user input and intelligently handles decimal precision by only showing decimal points when necessary (e.g., after division). The layout consists of a result display panel and a grid of buttons for digits and operators.

## Features:
- Perform basic arithmetic operations: Addition, Subtraction, Multiplication, and Division.
- Displays integers without unnecessary decimals, but handles floating-point operations when required.
- AWT-based functional and minimalistic GUI.
- Easy to use, responsive button grid.

## How to Run:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/java-calculator.git
   ```

2. Navigate to the project directory:
   ```bash
   cd java-calculator
   ```

3. Compile the Java files:
   ```bash
   javac Calculator.java
   ```

4. Run the application:
   ```bash
   java Calculator
   ```

## Creating a JAR File:

To package the calculator as an executable JAR file, follow these steps:

1. Compile the Java source files:
   ```bash
   javac Calculator.java
   ```

2. Create a manifest file `MANIFEST.MF` containing the main class:
   ```plaintext
   Main-Class: Calculator
   ```

3. Package the compiled files into a JAR:
   ```bash
   jar cfm CalculatorApp.jar MANIFEST.MF *.class
   ```

4. Run the JAR file:
   ```bash
   java -jar CalculatorApp.jar
   ```
