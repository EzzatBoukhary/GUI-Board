# Java GUI Random Board Generator

This Java GUI project generates random boards for gaming purposes. It was created as part of an Object-Oriented Programming (OOP) course at UCF. The application utilizes various interfaces, abstract classes, and inheritance to achieve a modular and structured design.

## Features

- **GUI Structure**: The project follows a well-defined GUI structure consisting of interfaces and abstract classes.
- **Initialization**: The `initialization` class initializes the game board with random elements, including walls, entrance, exit, and obstacles/rewards.
- **Custom GUI Components**: Utilizes custom `JPanel` classes for drawing colored halves of the game board.
- **Dynamic Drawing**: The `jframe` class dynamically draws different elements on the board based on their type.
- **Save Functionality**: Provides functionality to save the generated board to a file for later use.
- **Object-Oriented Design**: Implements various abstract classes and concrete classes to represent different elements on the board, such as obstacles, rewards, walls, and coins.

## Structure Overview

The project consists of several key classes and interfaces:

1. **GUI Interface**: Defines methods for menu and board output.
2. **Initialization Class**: Responsible for initializing the game board with random elements.
3. **JFrame Blueprint Abstract Class**: Provides a blueprint for adding images to the GUI.
4. **JFrame Class**: Manages the graphical representation of the game board.
5. **Main Application Classes**: Includes classes for managing the game board, frames, and user interactions.
6. **Test Class**: Contains the main method to launch the application.

## Report and Chart of OO Design

For a detailed report on the project and a chart of OO Design, please refer to [Report.pdf](Report.pdf) located in the repository.

## Usage

1. Clone the repository to your local machine.
2. Compile and run the `testclass1` class.
3. Use the menu options to design a new board or load an existing one.
4. Explore the generated boards and interact with the GUI elements.


## Dependencies

- Java Development Kit (JDK)
- Swing GUI Library

## Screenshots

### Main Menu
![Main Menu](mainMenu.jpg)

### Board
![Board](board.jpg)
