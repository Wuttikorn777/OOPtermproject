# 🍄 OOP Term Project: Mario-Style 2D Platformer

![Java](https://img.shields.io/badge/Language-Java_17%2B-orange?style=for-the-badge&logo=java)
![LibGDX](https://img.shields.io/badge/Framework-LibGDX-red?style=for-the-badge&logo=libgdx)
![Gradle](https://img.shields.io/badge/Build_Tool-Gradle-02303A?style=for-the-badge&logo=gradle)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

> **A Mario-inspired 2D platformer developed in Java to demonstrate robust Object-Oriented Programming (OOP) principles.**

This project is part of the Object-Oriented Programming course. It serves as a practical application of software design patterns, utilizing the **LibGDX** framework to create a functional and scalable game engine.

## ✨ Key Features

### 🎮 Gameplay Mechanics
* **❤️ Dynamic Health System:** The player starts with 3 hearts. Health depletes upon collision with enemies or environmental hazards.
* **🪙 Collectibles & Scoring:** Includes a system for collecting coins (score) and heart items (health restoration).
* **🌵 Physics & Collision:** Implemented precise collision detection logic between the player, terrain, and hazardous objects.
* **🏃 Fluid Movement:** Smooth character controls implementing velocity, acceleration, and gravity mechanics.

### 🧩 OOP Design & Architecture
This project focuses heavily on clean code structure:
* **Modular Design:** Classes are strictly separated based on responsibility (SRP) — e.g., `Player`, `Item`, `Hazard`, and `HUD`.
* **Inheritance & Polymorphism:** Utilizes a base class strategy for Game Objects. This allows for easy extensibility (e.g., adding new enemy types) without modifying the core engine.
* **Separation of Concerns:** Distinct separation between the Game Logic (Update loop) and the Rendering Layer (Draw loop).

## 🛠️ Tech Stack

* **Language:** Java (JDK 17 or 21)
* **Framework:** LibGDX (Cross-platform game development framework)
* **Build Tool:** Gradle
* **IDE:** VS Code / IntelliJ IDEA

## 🚀 Getting Started

Follow these steps to run the game on your local machine.

### 1. Prerequisites
Ensure you have the following installed:
* **Java JDK 17** or higher
* **Git**

### 2. Installation & Run

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/Wuttikorn777/OOPtermproject.git](https://github.com/Wuttikorn777/OOPtermproject.git)
    ```

2.  **Navigate to Project Directory**
    ```bash
    cd OOPtermproject
    ```

3.  **Run the Game**
    * **Windows (PowerShell/CMD):**
        ```bash
        .\gradlew desktop:run
        ```
    * **macOS / Linux:**
        ```bash
        ./gradlew desktop:run
        ```

