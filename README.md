# Rock Blaster

A classic Asteroids arcade game implementation.

## Description

This project is a recreation of the classic Asteroids arcade game, featuring spaceship controls, asteroid destruction, and collision detection.

## Requirements

- Python 3.8+
- pygame

## Installation

1. Clone or download this repository
2. Install dependencies:
    ```powershell
    # Create a virtual environment
    python -m venv .venv

    # Activate (PowerShell)
    # Use this in PowerShell (Windows):
    .\.venv\Scripts\Activate

    # Activate (Bash / POSIX shells)
    # Use this in Bash, WSL, macOS or Linux:
    source .venv/bin/activate

    # Then install pygame into the active environment
    pip install pygame

    # OR: install pygame directly into the project (target) folder
    # From the project root (installs into the current folder):
    python -m pip install --target . pygame

    # OR: specify an absolute target folder (Windows example):
    python -m pip install --target "c:\\Users\\USER_NAME\\OneDrive\\Desktop\\Asteroids\\asteroids" pygame
    ```

## Running the Game
Execute the following command from the project directory:

```bash
python main.py
```

Use w,a,d,s to move, spacebar to shoot, and destroy all asteroids to advance levels.
