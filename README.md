# Pong Game with Scoreboard

## Overview
This is a **classic Pong game** implemented using Python's **Turtle graphics** module. The game features a ball that bounces between two paddles, and a scoreboard to keep track of the players' scores. Each time a player misses the ball, the opponent scores a point. The game gets progressively faster with each bounce.

## Features
- **Two-player Pong game** with controllable paddles
- **Scoreboard** to track points for each player
- Ball speed increases with every bounce for added difficulty
- Ball resets in the center of the screen after each missed ball
- Simple graphics and smooth gameplay using Python’s Turtle library

## Controls
- **Player 1 (Left Paddle)**:  
  - Move Up: `W`  
  - Move Down: `S`

- **Player 2 (Right Paddle)**:  
  - Move Up: `Up Arrow`  
  - Move Down: `Down Arrow`

## Requirements
- Python 3.x
- Turtle graphics module (pre-installed with Python)

## How to Play
1. Clone the repository or download the source code.
   
   ```bash
   git clone https://github.com/tomwoolye/pong-game.git
   ```

2. Navigate to the project folder:

   ```bash
   cd pong-game
   ```

3. Run the Python script:

   ```bash
   python pong_game.py
   ```

4. Use the keyboard controls to move your paddle. Try to prevent the ball from passing your paddle while aiming to make the ball go past your opponent's paddle.

5. The scoreboard will update each time a player scores a point. The game continues indefinitely, with increasing ball speed.

## Code Structure

### `pong_game.py`
This file contains the main game logic, including:
- Paddle movement
- Ball movement and bouncing logic
- Score tracking and display

### `ball.py`
Defines the ball class responsible for handling ball movement and speed, as well as bouncing mechanics.

### `paddle.py`
Defines the paddle class responsible for moving the paddles based on user input.

### `scoreboard.py`
Manages the scoreboard, updating and displaying the current scores for both players.

## Customization
You can customize the game by tweaking:
- **Ball speed**: Adjust the initial speed or speed increment after each bounce.
- **Paddle size**: Modify the paddle's height and width for different levels of difficulty.
- **Score limit**: Add a score limit or winning condition if you want the game to end after a certain number of points.

## Example Gameplay

The game starts with the ball in the center of the screen, and both players controlling their paddles. The ball will increase in speed after every hit, making the game more challenging over time. The first player to miss the ball causes the opponent to score a point.


## Acknowledgments
This project was inspired by the **100 Days of Code: The Complete Python Pro Bootcamp** by **Dr. Angela Yu**. The course provided an excellent foundation in Python and game development concepts, which were instrumental in building this Pong game.

You can check out the course [here](https://www.udemy.com/course/100-days-of-code/).

---

## License
This project is open-source under the **MIT License**. Feel free to use, modify, and distribute as you like.

---

## Author
Created by **[Tom Wooliscroft](https://www.linkedin.com/in/tom-wooliscroft-b5b177a5/)**. You can find more of my projects on [GitHub](https://github.com/tomwooly).

---

### Happy Playing!

---

