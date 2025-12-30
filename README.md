# C++: Game Software Engineering
**University Year 1 | Semester 2**

A comprehensive study of Software Engineering principles in C++, demonstrating advanced Object-Oriented Programming (OOP), custom-built data structures, and state-based AI.

> **[🔗 View the full technical breakdown on my Portfolio](https://sites.google.com/view/myles-coleman/projects/game-software-engineering)**

## 📺 Video Showcase
[![Snake Game Showcase](https://img.youtube.com/vi/iVbCAqijkKo/0.jpg)](https://www.youtube.com/watch?v=iVbCAqijkKo)
*Click the image above to view the gameplay and AI behaviour in action.*

## 🕹️ Project Overview
This repository documents my progression through the Game Software Engineering module. It begins with foundational library integration and culminates in a complex, multi-system implementation of Snake, featuring custom memory management and automated agents.

## 📂 Repository Contents

### 1. 01-SFML-Introduction
* **Purpose:** Initial technical exploration of the SFML library.
* **Logic:** Foundational prototypes focused on the render loop, real-time event polling, and basic sprite transformation.

### 2. 02-Snake-Game
A high-level implementation of Snake engineered to demonstrate architectural design patterns.
* **Custom Doubly Linked List:** Engineered a bespoke Linked List from scratch to manage snake segment growth and coordinate movement, demonstrating low-level data structure implementation without relying on standard library containers.
* **State-Based AI Behaviour:** Developed an automated AI snake utilizing cardinal state validation and pathing logic to navigate the board and collect items.
* **Modular OOP Architecture:** Separated core concerns into specialized classes (e.g., `InputManager`, `GameData`, `Collectable`) to ensure high maintainability and scalability.
* **Technical Documentation:** Includes a full **UML Diagram** mapping the inheritance structures and class relationships within the engine.

## 🛠️ Technical Skills Demonstrated
* **Software Architecture:** Class modularity, interfaces, and clean code principles.
* **Memory Management:** Safe handling of dynamic nodes within the Linked List.
* **Game Logic:** Collision detection, score persistence, and AI state-checks.

## 💻 Technical Specs
* **Language:** C++
* **Library:** SFML 3.0.0
* **Compiler:** Visual Studio
