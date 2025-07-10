# 🧟‍♂️ Zombie Arena

![Zombie Arena Banner](assets/banner.png)

> A fast-paced 2D top-down shooter built in **C++** using **SFML**. Survive increasingly difficult waves of zombies, collect health and ammo pickups, and become the last survivor standing!

---

## 🎮 Game Overview

**Zombie Arena** is a 2D top-down shooting game where you take on waves of zombies in a shrinking battlefield. The game tests your reflexes, accuracy, and strategy as you survive longer and longer against relentless undead enemies.

---

## 🔥 Game Features

- 🎯 **Top-down shooter mechanics**
- 🧠 **Basic zombie AI** that tracks the player
- 💊 **Pickup system**: health and ammo
- 🔫 **Shooting and bullet physics**
- 🗺️ **Dynamic arena generation**
- 📈 **Score and wave tracking**
- 🎮 **Smooth WASD & mouse controls**

---

## 🕹️ Controls

| Key / Mouse | Action          |
|-------------|------------------|
| `W`         | Move Up          |
| `A`         | Move Left        |
| `S`         | Move Down        |
| `D`         | Move Right       |
| `Mouse`     | Aim & Shoot      |
| `ESC`       | Quit Game        |

---

## 📸 Screenshots

> _Add these images to an `/assets/` folder in your project directory._

### 🔫 Gameplay Screenshot
![Gameplay](assets/gameplay.png)

### 🧟 Zombie Swarm
![Zombies](assets/zombies.png)

### 🗺️ Arena Overview
![Arena](assets/arena.png)

---

## 📁 Project Structure
ZombieArena/
├── ZombieArena.cpp # Main game loop and event handling
├── Player.cpp # Player movement, shooting, and health
├── zombie.cpp # Zombie spawning and tracking logic
├── bullet.cpp # Bullet firing, movement, and collisions
├── pickup.cpp # Health and ammo pickup spawning and effects
├── arena.cpp # Arena layout and boundaries
├── assets/ # All textures, sounds, and screenshots
└── README.md # This file


---

## ⚙️ Build & Run

### 📌 Requirements

- C++17 or later
- [SFML 2.5+](https://www.sfml-dev.org/)
- g++ or Visual Studio (or any C++ compiler)

### 🧪 Compile

#### Linux / macOS (Terminal)

```bash
g++ ZombieArena.cpp Player.cpp zombie.cpp bullet.cpp pickup.cpp arena.cpp \
    -o ZombieArena \
    -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio
./ZombieArena


Windows (Visual Studio)
Create a new SFML project

Add all .cpp files to the solution

Link SFML libraries (graphics, window, system, audio)

Build and run

💡 Future Ideas
🧠 Smarter zombie behavior (pathfinding)

🌍 Larger arenas and multiple levels

💥 Explosives and weapon upgrades

💾 Save/load high scores

🎮 Gamepad/controller support

👤 Developer
Saurav Kumar
Assistant Professor, Dept. of CSE
Siksha 'O' Anusandhan University
📧 saurav@example.com

📜 License
This project is licensed under the MIT License.



