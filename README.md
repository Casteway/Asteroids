# Asteroids

> **Note:** This is a guided project from [Boot.dev](https://www.boot.dev). A significant amount of the foundational structure and heavy-lifting was provided by their backend development curriculum. This repository represents my implementation of the application.

Asteroids is a classic arcade-style 2D space shooter built using Python and the Pygame library. In this game, the player controls a spaceship navigating through an asteroid field. The objective is to shoot and destroy the asteroids, which break into smaller fragments upon impact, while avoiding collisions to survive.

## Features

* **Physics & Movement:** Smooth spaceship controls featuring rotation and forward thrust.
* **Collision Detection:** Accurate hitboxes for the player, lasers, and asteroids to register impacts and destruction.
* **Dynamic Asteroids:** Asteroids spawn dynamically at the edges of the screen and split into smaller, faster projectiles when hit.
* **Pygame Rendering:** A clean, 60 FPS 2D graphical rendering loop.

## Prerequisites

* Python 3.x
* Pygame

## Installation

1. Clone the repository to your local machine: `git clone https://github.com/Casteway/Asteroids.git`
2. Navigate into the project directory: `cd Asteroids`
3. Create a virtual environment (optional but recommended): `python3 -m venv venv`
4. Activate the virtual environment:
   * On Linux/macOS: `source venv/bin/activate`
   * On Windows: `venv\Scripts\activate`
5. Install the required dependencies: `pip install -r requirements.txt` *(or `pip install pygame` if there is no requirements file)*

## Usage

Run the `main.py` script from the root directory of the project to launch the game window.

`python3 main.py`

## Controls

* **W / Up Arrow:** Accelerate forward
* **A / Left Arrow:** Rotate counter-clockwise
* **D / Right Arrow:** Rotate clockwise
* **Spacebar:** Shoot lasers
