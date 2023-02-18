# Pong-the-famous-arcade-game
 This Python code is a program that simulates the classic game Pong.
It imports necessary modules such as Screen, Bat, Ball, and Scoreboard. It also tkinter to set up the game window with dimensions of 800 by 600 pixels, a black background, and a title of "Pong". The program sets the screen tracer to 0 so that the animations are not displayed until the screen is updated.

An instance of the Scoreboard class is created to display the scores, and two instances of the Bat class are created to represent the left and right bats respectively. The Ball class is also instantiated to represent the ball used in the game.

The program listens to keyboard inputs from the user to control the movement of the left and right bats, which are set to the 'w', 's', 'Up', and 'Down' keys.

The game loop begins with a boolean variable game_on being set to True. In the loop, time.sleep is used to pause the program execution for a short amount of time. The screen is updated, and the ball's movement is updated using the ball's move method. The program also detects collisions of the ball with the top and bottom walls and the bats, with the ball's bounce_x and bounce_y methods being called to change the ball's direction of movement.

If the ball passes the left or right edge of the screen, the ball is reset using the refresh method, and the Scoreboard's l_point or r_point method is called to increment the corresponding score.

The program exits when the user clicks the exit button on the screen.