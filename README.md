# Tetris-with-GUI

A classic Tetris game built with C++ and C, featuring a graphical user interface implemented with SFML.

## Features

- Classic Tetris gameplay with falling tetrominoes, line clearing, and increasing levels.
- Intuitive graphical user interface for easy and engaging play.
- Score tracking and level progression as you clear lines.
- Responsive keyboard controls for movement and rotation.
- Special "bomb" piece for clearing blocks.

## Technologies

- **C++ / C:** Core logic and performance.
- **SFML:** Rendering graphics, handling window events and input.

## Getting Started

### Prerequisites

- C++ compiler (e.g., g++, clang++)
- [SFML library](https://www.sfml-dev.org/)

### Build & Run

1. Clone the repository:
    ```sh
    git clone https://github.com/AyaanKhan1576/Tetris-with-GUI.git
    cd Tetris-with-GUI
    ```
2. Install SFML.
3. Compile the project (adjust the command as needed for your setup):
    ```sh
    g++ main.cpp -o tetris -lsfml-graphics -lsfml-window -lsfml-system
    ```
4. Run the game:
    ```sh
    ./tetris
    ```

## License

This project is licensed under the MIT License.
