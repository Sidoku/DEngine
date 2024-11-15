DEngine
===========
<div align="center">
    <img width="30%" src="StartScreen.png">
</div>

## Project Concept

DEngine is a game engine built in C++ using the SDL2 library. The engine allows users to create custom Dungeons crawlers. Project website: https://posnil.wixsite.com/dengine/

## Table Of Contents

- [Snapshots](#Snapshots)
- [Getting Started](#getting-started)
    + [1. Download and Installation](#1-Download-and-Installation)
    + [2. Run the editor](#2-Run-the-Editor)
    + [3. Start-the-Game](#3-Start-the-Game)
    + [4. Different customizations offered](#4-Different-customizations-offered)
- [Play the Game](#Play-the-Game)
- [My Roles and Responsibilities](#my-roles-and-responsibilities)
- [Contact](#Contact)

## Snapshots

#### DEngine

Below are some screenshots of the game:

<p align="center">
<img height="500" width="300" src="Gameplay1.png">
<img height="500" width="300" src="Gameplay2.png">
<img height="500" width="300" src="Gameplay3.png">
</p>

## Getting Started

### 1. Download and Installation

First, download and install these libraries:
1. SDL2: Go to the SDL2 website and download the latest version of SDL2 for your platform
2. SDL2_tff: Go to the SDL2_ttf website and download the latest version of SDL_ttf for your platform
3. SDL2_mixer: Go to the SDL2_mixer website and download the latest version of SDL2_mixer for your platform
4. Pybind: To install Pybind, you need to have Python 3 and pip installed on your system. Open a command prompt and enter the command "pip install pybind11" to install Pybind.
5. Tkinter: To install Tkinter, you need to have Python 3 and pip installed on your system. Open a command prompt and enter the command "pip install python-tk" to install Tkinter.
6. Pillow: To install Pillow, you need to have Python 3 and pip installed on your system. Open a command prompt and enter the command "pip install Pillow" to install Pillow

### 2. Run the Editor

1. Go to the Engine folder
2. Edit the macbuild.py file to match your Python version
3. Run the command: python3 macbuild.py
4. Now run the command: python3 EditorIntergrated.py

### 3. Start the Game
There are 2 ways to start the game:
1. One way is to click on "Start Random Game" to play the game with random customizations generated with 3 game levels.
2. The second way to start the game is to first customize the game according to the player's liking.

### 4. Different customizations offered​​

1. Customize rows and columns, interconnectivity (lower the interconnectivity higher the difficulty)
2. Players can also customize the monster count and treasure percentage wanted in the game
3. Players also get the option of picking between 2 different tile themes, 2 types of player characters to choose from, and 2 types of monsters
4. If the player wants to continue customizing the game, there is a "Customize Level" drop-down menu that will allow for adjusting the settings for individual levels.

After customization the player can start the game by clicking on "Start Game" and the game will start with the configured customizations.

## Play the Game

1. Use WASD or Arrow keys to move around the game world.
2. To perform actions, you need to roll dice. The dice roll determines the number of actions you can perform in that turn.
3. Press the "R" key to pick up the Axe.
4. You must have the Axe to defeat the monsters. Each monster requires 1 or 2 axe kills to die.
5. Press the spacebar to enter the attack stance and then press the direction key to attack in that direction.
6. Press the "T" key to pick up the treasure.
7. The game includes a maze, and your objective is to reach the end-level door without getting killed by monsters.

## My Roles and Responsibilities

- Implemented the resource manager
- Implemented the sprite loader
- Implemented the player controller

## Contact

* Siddharth Singhai - sidsinghai97@gmail.com
* [![LinkedIn][linkedin-shield]][linkedin-url]
* [![Portfolio][portfolioIcon-url]][portfolio-url]

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/siddharthsinghai97/
[portfolioIcon-url]: https://img.shields.io/badge/-Portfolio-brightgreen
[portfolio-url]: https://sidsinghai97.wixsite.com/portfolio
