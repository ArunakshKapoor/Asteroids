# 🪐 Asteroids Game (Python + Pygame)

This is a simple Asteroids-style arcade game developed using **Python** and **Pygame**. The project is inspired by the classic 1979 Atari arcade game and was built as a hands-on exercise to explore game loops, collision detection, object-oriented programming, and event handling in Python.

---

## 🎮 Gameplay Overview

- Control your spaceship using the arrow keys.
- Shoot bullets (`spacebar`) to destroy incoming asteroids.
- Avoid collisions with asteroids — one hit and it's game over!
- Asteroids spawn randomly and increase in number as time progresses.

---

## 🛠️ Tech Stack

- **Language**: Python 3.6
- **Library**: [Pygame](https://www.pygame.org/)

---

## 📦 Setup Instructions

1. **Clone the repo**:
```bash
git clone https://github.com/ArunakshKapoor/Asteroids.git
cd Asteroids
```
2. Install dependencies:
Make sure Python is installed. Then, install Pygame:
```
pip install pygame
```
3. Run the game:
```
python main.py
```

## Concepts Practiced
Game loop architecture

Object-oriented design for game entities

Event-driven programming (keyboard controls)

Collision detection and response

Sprite rendering and screen updates using Pygame

## Project Structure
```
Asteroids/
├── assets/               # Game assets (images, sounds)
├── game/                 # Core game logic (Ship, Asteroids, Bullets, etc.)
│   ├── __init__.py
│   ├── asteroid.py
│   ├── bullet.py
│   ├── ship.py
│   └── vector.py
├── main.py               # Main entry point and game loop
└── README.md             # Project documentation
```

## Future Enhancements (Optional Ideas)
Add a scoring system and high score tracking

Introduce different asteroid sizes and speeds

Add power-ups (e.g., shields, rapid-fire)

Add sound effects and background music

Mobile or web deployment using Pygbag or Pyodide


---

Let me know if you’d like a demo GIF added, GitHub badges, or instructions for bundling it into an executable!
