# Are-You-Worthy

A Python-based collection of OpenGL game and graphics experiments built with PyOpenGL/GLUT. This repository contains multiple prototype scripts exploring 3D environments, maze gameplay, dragon shooting, mountain scenes, and interactive visual effects.

## Project overview

This project looks like an iterative game development playground rather than a single final app. The files include several experimental versions of similar mechanics, such as:

- maze navigation and collectible gameplay
- 3D scene rendering with lighting and camera movement
- dragon and shooting mechanics
- background and atmospheric visual effects
- reusable templates for OpenGL-based projects

## Repository structure

```text
Are-You-Worthy/
├── background.py
├── maze.py
├── maze & moun.py
├── maze,mountain,dragon.py
├── mountain.py
├── mount&maze(delete_later).py
├── project2.0.py
├── project2.5.py
├── project3.0.py
├── project4.0.py
├── project_template.py
├── shoot_dragon.py
├── stars.py
├── template
└── README.md
```

## Main features

### 3D maze game
The `maze.py` script implements a 3D maze with:

- isometric camera view
- player movement with arrow keys
- collectible rewards and bombs
- minimap overlay
- timer and score system
- reset/restart behavior

### Game prototypes and experiments
Other files such as:

- `project2.0.py`
- `project3.0.py`
- `project4.0.py`
- `maze,mountain,dragon.py`
- `shoot_dragon.py`

appear to be evolving experimental builds combining maze, mountain, dragon, and shooting mechanics.

### Visual effects and scene demos
Files like `stars.py`, `background.py`, and `mountain.py` suggest a set of OpenGL visual studies for background scenes, sky effects, and 3D object rendering.

## Tech stack

- Python
- PyOpenGL
- GLUT / OpenGL Utility Toolkit
- 3D graphics rendering

## Requirements

Install the required dependencies:

```bash
pip install PyOpenGL PyOpenGL_accelerate
```

Depending on your operating system, you may also need an OpenGL/GLUT runtime installed:

- Ubuntu/Debian:

```bash
sudo apt-get install freeglut3-dev
```

- macOS: install GLUT via Homebrew or XQuartz tooling if needed
- Windows: ensure a compatible OpenGL/GLUT environment is configured for Python

## How to run

Most scripts are run directly with Python. For example:

```bash
python maze.py
```

You can also try other prototypes:

```bash
python project3.0.py
python shoot_dragon.py
python stars.py
python mountain.py
```

## Controls for the maze game

From `maze.py`:

- Arrow keys: move the player
- I / K: zoom in / out
- J / L: rotate the camera view
- B: bomb mode
- R: reset the game
- ESC: quit

## Notes

This repository is best understood as a learning and prototyping project in computer graphics and game development. The naming and file history suggest a progression of experiments rather than a single polished final product.

## Future improvements

Potential next steps for this project include:

- consolidating the best mechanics into one polished game
- adding sound effects and sprite art
- creating a main menu and level system
- separating reusable rendering helpers into modules
- improving project organization and documentation

## License

No explicit license file was found in the repository, so licensing information may be missing. If this project is intended for public reuse, consider adding an appropriate license file such as MIT or Apache-2.0.
