# Asteroids

A classic Asteroids arcade game implementation.

## Description

This project is a recreation of the classic Asteroids arcade game, featuring spaceship controls, asteroid destruction, and collision detection.

## Requirements

- Python 3.8+
- pygame

## Installation

### Getting the Code

You can get this project in two ways:

- **Clone the repository** (requires Git):
  ```powershell
  git clone https://github.com/Jlynn209/RockBlaster.git
  cd RockBlaster
  ```

- **Download from Releases** (no Git required):
  1. Go to the [Releases](https://github.com/Jlynn209/RockBlaster/releases) page
  2. Download the latest `.zip` file
  3. Extract the zip file to your desired location

### Install Dependencies

1. Navigate to the project directory
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
