# 🚗 Car Game

<div align="center">

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Pygame](https://img.shields.io/badge/Pygame-2.0+-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

**An exciting 2D car racing game built with Python and Pygame!**

*Dodge incoming cars, increase your speed, and beat your high score!*

[Features](#-features) • [Installation](#-installation) • [How to Play](#-how-to-play) • [Controls](#-controls) • [Screenshots](#-screenshots) • [Contributing](#-contributing)

</div>

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Installation](#-installation)
- [How to Play](#-how-to-play)
- [Controls](#-controls)
- [Game Mechanics](#-game-mechanics)
- [Screenshots](#-screenshots)
- [Project Structure](#-project-structure)
- [Technologies Used](#-technologies-used)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🎮 About

**Car Game** is a classic 2D endless runner-style racing game where players must navigate through traffic by dodging incoming cars. The game features multiple difficulty levels, score tracking, and an intuitive user interface. Built entirely with Python and Pygame, this project demonstrates fundamental game development concepts including collision detection, sprite management, and game state handling.

---

## ✨ Features

- 🎯 **Endless Gameplay** - Keep playing and dodging for as long as you can!
- 🚦 **Dynamic Difficulty** - Game speed increases as you progress through levels
- 🎨 **Multiple Car Sprites** - 7 different obstacle car designs for variety
- 📊 **Score Tracking** - Real-time score and dodged cars counter
- 👤 **Player Name Input** - Personalize your gaming experience
- ⏸️ **Pause Functionality** - Pause and resume anytime during gameplay
- 🎵 **Interactive Menu System** - Clean and intuitive navigation
- 🏁 **Countdown Timer** - 3-2-1-GO countdown before each game starts
- 💥 **Crash Detection** - Precise collision detection system
- 🎮 **Smooth Controls** - Responsive keyboard controls for optimal gameplay
- 📈 **Level Progression** - Advance through levels every 10 dodged cars
- 🔄 **Restart Option** - Quick restart from crash screen

---

## 🔧 Installation

### Prerequisites

Before running the game, ensure you have the following installed:

- **Python 3.7 or higher** - [Download Python](https://www.python.org/downloads/)
- **Pygame library** - Game development framework

### Step-by-Step Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/SairajJadhav08/Car-Game.git
   cd Car-Game
   ```

2. **Install Pygame**
   ```bash
   pip install pygame
   ```

3. **Verify installation**
   ```bash
   python -c "import pygame; print(pygame.ver)"
   ```

4. **Run the game**
   ```bash
   python game.py
   ```

---

## 🎯 How to Play

1. **Launch the game** by running `game.py`
2. **Enter your name** when prompted
3. **Click START** on the main menu
4. **Watch the countdown** (3-2-1-GO!)
5. **Dodge incoming cars** using arrow keys
6. **Accelerate or brake** using A and B keys
7. **Avoid collisions** with other cars and road boundaries
8. **Score points** for each car you successfully dodge
9. **Level up** every 10 dodged cars with increased difficulty

### Objective

- Dodge as many cars as possible without crashing
- Achieve the highest score
- Progress through increasing difficulty levels

---

## 🎮 Controls

| Key | Action |
|-----|--------|
| **← Left Arrow** | Move car left |
| **→ Right Arrow** | Move car right |
| **A** | Accelerate (increase speed) |
| **B** | Brake (decrease speed) |
| **P** | Pause game |
| **Mouse Click** | Navigate menus and buttons |

---

## 🎲 Game Mechanics

### Scoring System
- **+1 Dodged Car** for each obstacle successfully passed
- **Score = Dodged Cars × 10**
- Score is displayed in real-time at the top of the screen

### Level Progression
- **Level increases** every 10 dodged cars
- **Speed increases** with each level
- **Level notification** appears briefly on screen

### Collision Detection
- Crashes occur when:
  - Your car hits another car
  - Your car goes off the road (left or right boundaries)

### Game States
1. **Main Menu** - Start, Instructions, or Quit
2. **Name Input** - Enter player name
3. **Countdown** - 3-2-1-GO before gameplay
4. **Active Gameplay** - Main game loop
5. **Paused** - Game paused with options
6. **Crash Screen** - Game over with restart options

---

## 📸 Screenshots

### Main Menu
The game features an attractive main menu with options to start the game, view instructions, or quit.

### Gameplay
Experience smooth gameplay with dynamic backgrounds, multiple car sprites, and real-time score tracking.

### Instructions Screen
Detailed control instructions help new players get started quickly.

---

## 📁 Project Structure

```
Car-Game/
│
├── game.py                    # Main game file with all game logic
├── window.py                  # Window configuration (optional)
├── README.md                  # Project documentation
│
├── background.jpg             # Main menu background
├── background2.jpg            # Instructions screen background
├── download12.jpg             # Road/gameplay background
│
├── car1.jpg                   # Player car sprite
├── car.jpg                    # Obstacle car sprite 1
├── car2.jpg                   # Obstacle car sprite 2
├── car4.jpg                   # Obstacle car sprite 3
├── car5.jpg                   # Obstacle car sprite 4
├── car6.jpg                   # Obstacle car sprite 5
├── car7.jpg                   # Obstacle car sprite 6
│
├── yellow strip.jpg           # Road center line marker
└── strip.jpg                  # Road side line marker
```

---

## 🛠️ Technologies Used

- **Python 3.7+** - Core programming language
- **Pygame 2.0+** - Game development framework
  - Graphics rendering
  - Event handling
  - Collision detection
  - Sound and display management

### Key Python Concepts Demonstrated
- Object-oriented programming
- Event-driven programming
- Game loop implementation
- Sprite management
- Collision detection algorithms
- State management
- Random number generation
- File I/O operations

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help improve the Car Game:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/AmazingFeature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some AmazingFeature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/AmazingFeature
   ```
5. **Open a Pull Request**

### Ideas for Contributions
- Add sound effects and background music
- Implement high score persistence (save to file)
- Add power-ups and special items
- Create different game modes
- Improve graphics and animations
- Add mobile/touch controls
- Implement multiplayer functionality
- Add more car and background variations

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Contact

**Sairaj Jadhav**

- GitHub: [@SairajJadhav08](https://github.com/SairajJadhav08)
- Project Link: [https://github.com/SairajJadhav08/Car-Game](https://github.com/SairajJadhav08/Car-Game)

---

## 🌟 Acknowledgments

- Built with [Pygame](https://www.pygame.org/)
- Inspired by classic arcade racing games
- Thanks to the Python and Pygame communities for excellent documentation

---

<div align="center">

**If you enjoyed this game, please consider giving it a ⭐ star!**

Made with ❤️ and Python

</div>
