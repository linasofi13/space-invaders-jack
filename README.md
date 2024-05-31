# 🕹️ Space Invaders in Jack

Implementation of the retro video game "Space Invaders" in the Jack programming language, using the Nand to Tetris software for the Computer Organization course taught by Professor Edison Valencia at EAFIT University.

## Table of Contents
- [📖 Introduction](#-introduction)
- [✨ Features](#-features)
- [⚙️ Installation](#-installation)
- [🎮 Usage](#-usage)
- [🛠️ Classes and Methods](#-classes-and-methods)
- [🎯 Game Controls](#-game-controls)
- [🏆 Game Objective](#-game-objective)
- [🎥 YouTube Video](#-youtube-video)
- [👥 Contributors](#-contributors)

## 📖 Introduction
This project is a modern take on the classic "Space Invaders" arcade game, developed in the Jack programming language as part of the Nand to Tetris curriculum. The game was created for the Computer Organization course at EAFIT University, under the guidance of Professor Edison Valencia.

## ✨ Features
- **Classic Arcade Experience:** A faithful recreation of the beloved arcade game.
- **Advanced Shooting Mechanics:** Sophisticated handling of player and alien shots.
- **Smooth Gameplay:** Efficient management of game elements for an uninterrupted experience.

## ⚙️ Installation
To run this project, you will need to have the Nand to Tetris software installed on your machine. Follow these steps to get started:

1. Clone the repository:
   ```bash
   git clone https://github.com/linasofi13/space-invaders-jack.git
   cd space-invaders-jack
# Space Invaders in Jack

Welcome to the Space Invaders game implemented in the Jack programming language, using the Nand to Tetris software for the Computer Organization course taught by Professor Edison Valencia at EAFIT University.

## 🎮 Usage

After installing and setting up the project, you can play the game by following these steps:

1. Launch the Nand to Tetris software.
2. Load the project files.
3. Start the game and use the controls to play.

## 🛠️ Classes and Methods

### Alien

Manages the attributes and behaviors of an alien.

- **Constructor:** `Alien new(int posX, int posY, int index)`
- **Methods:** `dispose`, `draw`, `erase`, `getIndex`, `getX`, `getY`, `getDirection`, `changeDirection`, `movement`, `createShoot`, `getShoot`

### JuegoNave

Manages the game state and interactions.

- **Constructor:** `JuegoNave new()`
- **Methods:** `generateAliens`, `dispose`, `shootPathPlayer`, `shootPathAlien`, `playerWin`, `playerLoose`, `printPoints`, `printLives`, `naveCollision`, `run`

### LinkedList

Manages a list of aliens.

- **Constructor:** `LinkedList new()`
- **Methods:** `firstAlien`, `add`, `moverAlien`, `removeSpecificAlien`, `shootColisionAlien`, `getNextAlien`

### Main

Entry point for the game.

- **Function:** `void main()`

### Nave

Manages the player’s ship.

- **Constructor:** `Nave new()`
- **Methods:** `dispose`, `getX`, `getY`, `draw`, `erase`, `movement`, `createShoot`, `getShoot`

### Node

Manages individual nodes for the linked list.

- **Constructor:** `Node new(Alien newAlien)`
- **Methods:** `dispose`, `getAlien`, `getIndex`, `setNext`, `getNext`

### Shoot

Manages the bullets shot by the player and aliens.

- **Constructor:** `Shoot new(int posX, int PosY)`
- **Methods:** `dispose`, `draw`, `erase`, `getX`, `getY`, `shoot`

## 🎯 Game Controls

- ⬅️ **Left Arrow Key:** Move left
- ➡️ **Right Arrow Key:** Move right
- 🔫 **Space Bar:** Shoot
- ❌ **Q Key:** Quit the game

## 🏆 Game Objective

- **Winning:** The player wins the game by scoring 25 points, which means all aliens have been destroyed. A winning screen will be displayed.
- **Losing:** The player loses the game when their lives reach 0. A losing screen will be displayed.

## 🎥 YouTube Video

Watch the video showcasing the game on YouTube: [Space Invaders in Jack](https://www.youtube.com/watch?v=9Mz-jjKMquc).

## 👥 Contributors

This project was developed by:

- Mauricio Carrillo
- Lina Ballesteros
- Valentina Giraldo


