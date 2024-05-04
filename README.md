# SnakeGame
Python, Pycharm, OOP

Simple Snake Game with Turtle Graphics

This project is a simple snake game implemented using Python's turtle graphics module. 
The game consists of a snake controlled by the player, and the objective is to eat the food items 
to grow longer. The game ends when the snake collides with the screen boundaries or its own body.

![Screenshot 2024-05-04 235941](https://github.com/shanshee/SnakeGame/assets/135793255/a75be0bc-0bd5-4972-8af7-e636a2a84771)
![Screenshot 2024-05-05 000024](https://github.com/shanshee/SnakeGame/assets/135793255/d9bcc1d9-ac99-4446-98d2-fec0aff2d22c)
![Screenshot 2024-05-04 235753](https://github.com/shanshee/SnakeGame/assets/135793255/66e38c69-bc13-44ce-a423-799131b89830)

Features:

Snake Class: The Snake class represents the snake in the game. It allows the player to control 
the direction of the snake using arrow keys (up, down, left, right). The snake grows longer 
as it eats food items.

Food Class: The Food class represents the food items that the snake can eat. The food appears
as a red circle, and its position is randomly generated on the screen. When the snake eats the food,
a new food item is placed in a random position.

Scoreboard: The game includes a simple scoreboard that displays the player's score as they eat more
food items. The score increases with each successful meal.

Game Over: When the game ends (snake collides with the boundaries or itself), 
"GAME OVER" message is displayed on the screen.

Controls:

Use the arrow keys (up, down, left, and right) to control the snake's movement direction.
