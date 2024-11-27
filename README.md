# Minesweeper

This is a C++ project implementing the classic Minesweeper game. The project is structured with a focus on Object-Oriented Programming (OOP) principles, ensuring modularity and maintainability.

The game consists of three main code sections:

- **main.cpp**: The entry point that runs the game logic.
- **board.cpp**: Handles the structure and layout of the Minesweeper board.
- **game.cpp**: Manages the gameplay mechanics and rules.

To successfully run the code, you must download the custom header files **board.h** and **game.h**.

## Features

- A fully functional Minesweeper game with customizable grid size, mine number and difficulty.
- Clear separation of concerns through modularized classes and files.

## Usage

Download the board.h and game.h files that are located in my repository and copy the code located in main.cpp and paste it into the main.cpp part in the IDE. 

Then create two more classes in the IDE named board.cpp and game.cpp then copy and paste the code in the board.cpp and game.cpp section in my repository.

Ensure board.h and game.h are in the appropriate directories for your IDE. For example, with Codeblocks:

Place board.h in the include directory.
Place game.h in the include directory.
insert the files that you downloaded by clicking projects and adding the files.
By adding these files the source code will allow the software to identify where board.h and game.h is located and what it does.

## Compile and Run the code:

Compile the program by clicking on the yellow gear on the top of the program.
Run the program by clicking on the green play button on the top of the program aswell.
TIP: You can Compile and Run at the same time by press the icon with the yellow gear and green play button.

## Gameplay

### Controls

The game is played through a command-line interface. You will be prompted to:

- Select a grid cell by entering its row and column number.
- Select how many mines to be in the game
- Then finally select the coordinate of which you think the mine is not located

### Objective

- Clear all non-mine cells without triggering a mine.

## Sample Example

![image_2024-11-26_214552799](https://github.com/user-attachments/assets/a9293ad1-b069-4b3b-8095-752abb85fcc0)

## Implementation

### Board Class (`board.cpp`)

The `Board` class is responsible for:

- Initializing the Minesweeper grid.
- Placing mines and calculating hint numbers.

### Game Class (`game.cpp`)

The `Game` class handles:

- Displaying the current state of the board.
- Managing player interactions.
- Validating inputs and actions.
- Determining win/loss conditions.

### Main (`main.cpp`)

The main file orchestrates the gameplay loop by:

- Initializing the game.
- Processing player inputs.
- Displaying the board and handling game flow.

## Future Enhancements

- Add difficulty presets (e.g., Beginner, Intermediate, Expert).
- Implement a graphical user interface (GUI).
- Add a timer to track player performance.
- Support saving and loading game progress.

## Contributing

Contributions are welcome! If you have ideas or improvements, feel free to create a pull request or open an issue.

-----
Enjoy Minesweeper
