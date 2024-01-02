
# Breakout Ball

## Overview

This is a simple implementation of the classic Breakout game using the Pygame library in Python. The game features a paddle, a bouncing ball, and bricks to break. The player's objective is to clear the screen of bricks by bouncing the ball off the paddle.

## Features

- **Paddle:** Control the paddle using the left and right arrow keys to prevent the ball from falling below the paddle.

- **Ball:** The ball bounces off walls, the paddle, and bricks. If the ball passes below the paddle, the player loses a ball.

- **Bricks:** Break the bricks by hitting them with the ball. Different colored bricks provide varying scores when broken.

- **Scoring:** Gain points by breaking bricks. The game ends when all bricks are cleared or when the player runs out of balls.

## Installation

1.  Clone the repository:
```bash
   git clone https://github.com/ankitstha/breakout-game.git
```
2. Install Pygame:
```bash
   pip install pygame
```
3. Run the game:
```bash
    python breakout_game.py
```
## Controls
- **Left Arrow Key:** Move the paddle to the left.
- **Right Arrow Key:** Move the paddle to the right.

## Dependencies
- Pygame library

## Sound Credits
- Brick sound: 'sounds/brick.wav'
- Paddle sound: 'sounds/paddle.wav'
- Wall sound: 'sounds/wall.wav'

## Acknowledgments

This game is based on the classic Breakout game and was created as a project to learn Pygame.
