# CALCULATOR USING JAVA AWT

## Project Title
Calculator Using Java AWT

## Introduction

This project is a desktop-based calculator application developed using Java AWT (Abstract Window Toolkit). The application provides a graphical user interface (GUI) that allows users to perform basic arithmetic calculations easily. It is designed to demonstrate the use of AWT components, event handling, and object-oriented programming concepts in Java.

The calculator performs common mathematical operations such as addition, subtraction, multiplication, and division. It provides a simple and interactive environment for users to enter numbers and obtain results instantly.

## Objective

The main objective of this project is:

- To understand Java GUI programming using AWT.
- To learn event-driven programming concepts.
- To implement arithmetic operations through a graphical interface.
- To develop a user-friendly calculator application.
- To gain practical knowledge of ActionListener and event handling.

## Technology Used

- Programming Language: Java
- GUI Framework: AWT (Abstract Window Toolkit)
- IDE: Eclipse / NetBeans / IntelliJ IDEA / VS Code
- JDK Version: Java 8 or above

## About AWT

AWT (Abstract Window Toolkit) is a Java package used for creating graphical user interfaces. It provides various components such as:

- Frame
- Button
- Label
- TextField

AWT components rely on the native operating system's windowing system, making them platform-dependent.

## Features

The calculator application includes the following features:

1. Addition of two numbers
2. Subtraction of two numbers
3. Multiplication of two numbers
4. Division of two numbers
5. Clear function to reset values
6. User-friendly graphical interface
7. Event handling using ActionListener
8. Input validation
9. Instant result display
10. Lightweight and easy-to-use design

## Functional Requirements

The system should:

- Accept numerical input from users.
- Allow selection of arithmetic operations.
- Display calculation results.
- Handle invalid inputs gracefully.
- Clear all fields when requested.

## Non-Functional Requirements

- Simple and responsive interface.
- Easy navigation.
- Fast execution.
- Low memory consumption.
- Platform independence through Java Runtime Environment.

## Components Used

### Frame
Acts as the main window of the application.

### Label
Used to display text descriptions such as Number 1, Number 2, and Result.

### TextField
Used to accept input values from users and display results.

### Button
Used to trigger arithmetic operations and clear data.

### ActionListener
Handles button click events and performs corresponding operations.

## Working Procedure

1. The user enters the first number.
2. The user enters the second number.
3. The user selects an operation by clicking the corresponding button.
4. The ActionListener captures the event.
5. The program processes the selected arithmetic operation.
6. The result is displayed in the result field.
7. The Clear button resets all input and output fields.

## Algorithm

Step 1: Start the program.

Step 2: Create a Frame.

Step 3: Add Labels, TextFields, and Buttons.

Step 4: Register ActionListener for all buttons.

Step 5: Read user inputs from TextFields.

Step 6: Convert inputs into numeric values.

Step 7: Perform the selected arithmetic operation.

Step 8: Display the result.

Step 9: If Clear button is pressed, clear all fields.

Step 10: End.

## Event Handling

The calculator uses ActionListener to handle button-click events.

When a button is pressed:
- ActionPerformed() method is invoked.
- The corresponding operation is identified.
- The calculation is executed.
- The result is displayed.

This demonstrates event-driven programming in Java.

## Advantages

- Easy to understand.
- Simple graphical interface.
- Useful for beginners learning Java GUI.
- Demonstrates AWT components effectively.
- Supports basic arithmetic calculations.
- Lightweight application.

## Limitations

- Supports only basic arithmetic operations.
- Does not include advanced scientific calculations.
- Limited graphical styling compared to Swing and JavaFX.
- Requires Java Runtime Environment.

## Future Enhancements

The calculator can be enhanced by adding:

- Scientific calculator functions.
- Square root calculations.
- Percentage operations.
- Memory functions.
- Keyboard support.
- Improved user interface using Swing or JavaFX.
- Dark mode and themes.
- Calculation history.

## Testing

The application was tested with various inputs:

Test Case 1:
Input: 10, 5
Operation: Addition
Output: 15

Test Case 2:
Input: 20, 8
Operation: Subtraction
Output: 12

Test Case 3:
Input: 6, 7
Operation: Multiplication
Output: 42

Test Case 4:
Input: 40, 5
Operation: Division
Output: 8

Result:
All arithmetic operations produced accurate outputs.

## Applications

- Educational projects
- Java GUI learning
- Event handling demonstrations
- Beginner programming practice
- College laboratory exercises

## Conclusion

The Calculator Using Java AWT project successfully demonstrates the implementation of a graphical user interface using AWT components and event handling using ActionListener. The application performs basic arithmetic operations efficiently and provides a practical understanding of Java GUI programming concepts. This project serves as a strong foundation for developing more advanced desktop applications in Java.

## References

1. Java Documentation by Oracle
2. Java AWT API Documentation
3. Java Programming Books
4. Object-Oriented Programming Concepts
5. Java GUI Development Tutorials

## Author

Project Name : Calculator Using Java AWT
Language     : Java
Technology   : AWT
Type         : Desktop GUI Application

Thank You
