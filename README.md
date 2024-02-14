# PACman Game using C++ and OpenGL

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

## Project Overview

Welcome to the PACman Game project developed as part of the 6th-semester Computer Graphics and Visualization course. This game is implemented in C++ using the OpenGL package for graphics rendering.

### Project Team
- This projrct was done under guidance of Ms. Nalinakshi B. G.
  Assistant Professor
  Department of Computer Science and Engineering
  S.G.Balekundri Institute of Technology, Shivabasav Nagar
  Belagavi-590010
- [Sammed Bhistannavar 2BU20CS071](https://www.linkedin.com/in/sammed-bhistannavar-00b993227/)
- [Sunil Biradar 2BU20CS096]()
- [Sushant Hakare 2BU20CS097](https://www.linkedin.com/in/sushant-hakare-02b891227/)
- [Swapnadeep Kapuri](https://www.linkedin.com/in/swapnadeep-kapuri-5ab423228/)

## Game Overview

PACman is a classic arcade game where the player controls PACman to navigate a maze, consume dots, and avoid ghosts. The game has an engaging gameplay experience.

## Features

- Interactive PACman character.
- Ghost enemies with intelligent movement.
- Maze navigation and dot consumption.
- Power-ups for PACman.

## Project Structure

- **main.cpp:**
  - The main C++ source code file containing the game logic.
- **graphics.h, graphics.cpp:**
  - Files for graphics rendering using OpenGL.
- **assets/:**
  - Folder containing game assets such as textures and sounds.

## Dependencies

- **OpenGL:**
  - Ensure OpenGL is installed on your system.

- **Ubuntu Linux:**
  - Necessary to have Ubuntu 22.0 and above along g++ package installed in it.   

## Build and Run

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/SwapnadeepK/PacMan_using_OpenGL.git
    cd pacman-game
    ```

2. **Build and Compile:**

    ```bash
    g++ main.cpp graphics.cpp -o pacman -lGL -lGLU -lglut
    ```

3. **Run the Game:**

    ```bash
    ./pacman
    ```

## Screenshots

![PACman Game Screenshot available in PDF document](https://github.com/SwapnadeepK/PacMan_using_OpenGL/blob/main/Final_Reprt_CGV_1.pdf)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

