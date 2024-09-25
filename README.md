# Aim-tracker
Aim Tracker is a Python-based target practice game built using the Pygame library. The goal of the game is to click on growing and shrinking targets before they disappear. It's designed to help improve your mouse accuracy and reflexes.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Gameplay](#gameplay)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Aim Tracker game challenges you to click on dynamic, growing targets that appear at random locations on the screen. With limited lives, your goal is to hit as many targets as possible before they vanish. The game keeps track of your time, hits, misses, and accuracy.

## Features

- **Randomly appearing targets**: Targets appear at random positions on the screen.
- **Dynamic target size**: Targets grow to a maximum size and then shrink until they disappear.
- **Score tracking**: Tracks the number of hits, accuracy, speed, and the elapsed time.
- **Lives**: Players start with 3 lives; a life is lost if a target disappears before it's hit.
- **End screen**: Displays performance statistics including total hits, speed, and accuracy.

## Requirements

- **Python 3.x**
- **Pygame library** (`pygame`)
- **Requests library** (`requests`)

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/aim-tracker.git
    cd aim-tracker
    ```

2. **Install dependencies**:

    You can install Pygame and Requests using `pip`:

    ```bash
    pip install pygame requests
    ```

3. **Run the game**:

    ```bash
    python aim_tracker.py
    ```

## How to Play

1. **Start the game**: After running the script, the game window will open.
2. **Click the targets**: When a red and white target appears, click on it before it disappears.
3. **Track your stats**: At the top of the screen, you'll see your elapsed time, hit count, speed, and remaining lives.
4. **Game over**: The game ends when you run out of lives. An end screen will display your accuracy, total hits, and other statistics.

### Controls

- **Mouse**: Click on the targets to score points.
- **Keyboard**: Press any key to exit the game when on the end screen.

## Contributing

If you would like to contribute to this project, feel free to fork the repository, create a new branch, and submit a pull request. Suggestions for improvements, new features, or bug reports are welcome.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.
