# Maze Runner Game

## Overview

Maze Runner Game is an interactive game where players navigate through mazes, find a key and avoid obstacles. The game features a player character, enemies, keys, traps, and various objects within maze levels.

## Features

- **Player Character:** Control a character through arrow keys to navigate the maze.
- **Enemies:** Dynamic enemies that move around the maze.
- **Keys:** Collect keys to unlock exit doors.
- **Traps:** Static traps that can reduce the player's lives.
- **Hearts:** Collect hearts to gain additional lives.
- **HUD (Heads-Up Display):** Display of lives and collected key.
- **Multiple Levels:** Navigate through different maze levels.

## Gameplay

- **Controls:**
    - Use the arrow keys (UP, DOWN, LEFT, RIGHT) to move the player character.
    - Collect keys to unlock exit doors and win or go to the next level.
    - Avoid traps and enemies in order to stay alive.
    - Collect hearts to gain extra lives.

Enjoy the game!

## Screenshots

![Start screen Screenshot](png/screenshots/screenshotStartScreen.png)
![Menu screen Screenshot](png/screenshots/menuscreen.png)
![Gameplay Screenshot](png/screenshots/gameplay.png)


## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- 
- [IntelliJ IDEA](https://www.jetbrains.com/idea/)
- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html)
- [LibGDX framework](https://libgdx.badlogicgames.com/)


### How to open the game:

1. **Open the project:**

   Open the project in your preferred IDE or build tools.

3. **Build and run:**

   Build and run the game.

## Game Controls

- **Arrow keys:** Move the player character in different directions.
- **ESC key:** Pause the game or exit the current screen.

## Gameplay

### Objective

Navigate through the maze, collect key to unlock exits, and avoid traps and enemies.

### Health System

- The player has a limited number of lives.
- Collecting hearts restores health.
- Contact with traps or enemies causes health damage.

### Game Over

The game ends when all lives are exhausted.

### Victory

The player wins when he goes through the exit with a key.

## Development

The game is developed using the LibGDX framework. Here are some key aspects of the development:
### Screens

#### Start Screen

- Introduces the game.

#### Menu Screen

- The entry point of the game.
- Options to start the game, go to the level selection screen or explore our credits screen, and exit.

#### Game Screen

- The main gameplay screen.
- Displays the maze, player character, enemies, and other game elements.

### Game Objects

#### Player Character

- Represents the user-controlled character.
- Controlled through keyboard input.
- Animations for different movements.

#### Enemy

- AI-controlled characters.
- Move through the maze with randomized patterns.
- Collision with the player results in loss of lives.

#### Exit

- Marks the end of the level.
- Unlocked by collecting key.

#### Trap

- Hazards placed in the maze.
- Collision results in loss of lives.

#### Key

- Collectibles to unlock exits.

#### Heart

- Collectibles to restore player health.
- Adds to the life count.


#### Structure:
  - The game is structured using object-oriented principles.
  - The `GameObject` class provides a foundation for game objects.
  
- **Animation:**
    - Character and enemy animations are loaded from sprite sheets.
    - Animation sequences are controlled through LibGDX's `Animation` class.

- **Collision Detection:**
    - Collision detection is implemented to handle interactions with walls, keys, exits, traps, enemies, etc.

## Contributing

We welcome contributions to improve the game! If you'd like to contribute:

1. Email us your idea here: go72num@mytum.de

## Acknowledgements

We'd like to express gratitude to the following:

- [LibGDX](https://libgdx.badlogicgames.com/): The framework powering the game.
- Music Credits: [OpenGameArt](https://opengameart.org/)
- Sponsors: [TUM](https://www.chn.tum.de/de)
