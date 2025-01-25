# Pong Game

This is a classic Pong game implemented using Python's `turtle` graphics library. The game consists of two paddles, a ball, and a scoreboard. The goal of the game is to prevent the ball from passing your paddle while trying to get it past your opponent's paddle to score points.

## Features

- Two paddles controlled by the players.
- Ball that bounces off the top and bottom walls.
- Ball that bounces off the paddles when hit.
- Scoreboard that keeps track of the score.
- Speed of the ball increases after hitting a paddle.
- Simple keyboard controls for both players.

## Requirements

- Python 3.x
- `turtle` graphics library (typically included with Python)

## Controls

- **Right Paddle (Player 1)**:  
  - Move up: `Up Arrow`  
  - Move down: `Down Arrow`

- **Left Paddle (Player 2)**:  
  - Move up: `W`  
  - Move down: `S`

## How to Play

1. Run the Python script.
2. Player 1 uses the `Up` and `Down` arrow keys to control the right paddle.
3. Player 2 uses the `W` and `S` keys to control the left paddle.
4. The game continues until the players quit the game.
5. The score is displayed at the top of the screen.

## Game Flow

- The game starts with both paddles and the ball on the screen.
- The ball moves at a constant speed until it hits the top or bottom walls, at which point it bounces.
- When the ball hits a paddle, it bounces back, and the ball’s speed increases slightly to make the game more challenging.
- If the ball passes one of the paddles, the other player scores a point, and the ball resets to the center of the screen.
- The score updates accordingly for each player.

## File Structure

pong_game.py # Main game logic and classes (Ball, Paddle, Scoreboard)
paddle.py # Class for paddles
ball.py # Class for the ball
scoreboard.py # Class for the scoreboard



## How to Run

1. Download or clone this repository to your local machine.
2. Open a terminal or command prompt in the folder containing the `pong_game.py` file.
3. Run the game by executing:

```bash
python pong_game.py
