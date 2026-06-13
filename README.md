# 🧱 Brick Breaker Game

A classic Brick Breaker arcade game developed using Python and Pygame. The project demonstrates object-oriented programming principles, real-time game mechanics, collision detection, and graphical rendering.

##  Overview

This game allows players to control a paddle to bounce a ball and destroy bricks arranged in a grid. The objective is to clear all bricks while preventing the ball from falling below the paddle.

The project was built to strengthen skills in:

- Python Programming
- Object Oriented Design
- Game Development
- Event Handling
- Collision Detection
- Real Time Rendering using Pygame

---

##  Features

- Interactive paddle movement
- Ball physics and bouncing mechanics
- Brick collision detection
- Dynamic brick grid generation
- Real-time score tracking
- Game Over screen
- Smooth gameplay with frame-rate control
- Modular and maintainable code structure

---

## 🛠 Technologies Used

- Python
- Pygame

---

##  Project Structure

```text
BrickBreaker/
│
├── settings.py
├── ball.py
├── paddle.py
├── brick.py
├── main.py
└── assets/
```

### Components

#### Ball Class
- Controls ball movement
- Handles wall collisions
- Updates ball position continuously
- Interacts with paddle and bricks

#### Paddle Class
- Controlled by keyboard input
- Restricted within screen boundaries
- Deflects the ball upon collision

#### Brick Class
- Represents individual bricks
- Tracks active/inactive state
- Disappears when hit
- Contributes to score progression

---

##  Gameplay

### Controls

| Key | Action |
|------|---------|
| Left Arrow | Move paddle left |
| Right Arrow | Move paddle right |
| Close Window | Exit game |

---

### Objective

Destroy all bricks by bouncing the ball off the paddle while preventing the ball from falling below the screen.
---

##  Configuration

Game settings are centralized and can be easily modified:

- Screen Width: 800 px
- Screen Height: 600 px
- Paddle Width: 120 px
- Paddle Height: 20 px
- Adjustable Ball Speed
- Configurable Brick Rows and Columns
---

##  Learning Outcomes

Through this project, I gained practical experience in:

- Object-Oriented Programming (OOP)
- Python Game Development
- Real-Time Event Processing
- Collision Detection Algorithms
- Modular Software Design
- Graphics Rendering with Pygame
---

##  Future Improvements

- Multiple levels
- Power-ups
- Sound effects and background music
- High score system
- Lives system
- Different brick types
- Pause and restart functionality

---
##  Authors

- Mahdiat Rahman
- Md. Golam Rabbani Sajib
- Rabeta Tanjum Arni

---
