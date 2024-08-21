Game Overview: This is a classic Snake game implemented in Python using the Turtle module. The game is controlled using the arrow keys, and it features three main classes: Snake, Scoreboard, and Food.

Gameplay: The objective of the game is to eat as much food as possible while avoiding collision with the wall or the snake's own body. The game ends when the snake collides with the wall or its own body.

Classes

Snake Class
The Snake class represents the snake in the game. It has the following attributes and methods:

head: The head of the snake, represented by a Turtle object.
segments: A list of Turtle objects representing the snake's body.
create_snake(): Creates the original snake segment.
move(): Moves the snake in the specified direction.
extend(): Adds a new segment to the snake's body.
up():, down():, left():, right(): These methods ensure that the snake cannot turn back into itself when controlled.

Scoreboard Class
The Scoreboard class represents the scoreboard in the game and is displayed as a Turtle object. It has the following attributes and methods:

score: The current score of the game.

update_scoreboard(): Updates the current score in the game.
increase_score(): Updates the score as your snake grows. 
gave_over(): Used to display the Game Over message when certain conditions are met. 

Food Class
The Food class represents the food in the game. It has the following attributes and methods:

food: A Turtle object representing the food.
refresh(): Spawns a new food item at a random location on the screen every time the previous food item comes into contact with the snake. 

Included Files:
main.py: The main file to play the game.
snake.py: The Snake Class.
scoreboard.py: The Scoreboard Class.
food.py: The Food Class.
