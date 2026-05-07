# 🕹️ Cyberpunk Revolution (2D Fighting Game)

## Overview
**Cyberpunk Revolution** is an arcade-style 2D fighting game developed entirely from scratch using **Java** and **JOGL (Java Bindings for OpenGL)**. The project abandons modern graphical game engines to focus heavily on core Object-Oriented Programming principles, low-level rendering, and creating a scalable game architecture.

---

## ✨ Features

- **Game Modes:** Play against a scalable, intelligent AI (`Single Player`) or battle a friend (`Multiplayer`).
- **Dynamic AI Controller:** The computer opponent (`AIController.java`) scales in difficulty across 6 levels, adjusting its aggression, defensive maneuvers, and reaction time dynamically.
- **Complex State Management:** Implemented a robust state machine (`Game.State`) to seamlessly transition between multiple screens (Main Menu, Character Select, Settings, Pause, Gameplay, Credits).
- **Custom Animation Engine:** Engineered a `SpriteAnimator` and `PlayerAnimator` to handle sprite sheets for idle, walk, attack, and hit states.
- **Collision & Physics:** Handled 2D bounding-box hit detection for special powers, physical attacks, and health reduction calculations.
- **Interactive UI:** Custom-built interactive buttons, power bars, health bars, and text rendering overlays.

---

## 🛠️ Tech Stack

- **Language:** Java
- **Graphics API:** JOGL (Java Open Graphics Library)
- **Key Concepts:** OOP Architecture, State Machines, Real-time Game Loops, Artificial Intelligence algorithms, 2D Array Rendering.

---

## 💡 The "Why" Behind the Project
This project was an exercise in understanding the absolute fundamentals of software engineering and game development. Building a game loop, writing an AI algorithm from scratch, and managing memory/textures using raw Java/OpenGL pushed my understanding of algorithmic logic and system architecture far beyond traditional application development.

---
