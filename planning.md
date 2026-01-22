A place to write your findings and plans

## Understanding
(Buay) The main.cpp has the main includes such as core, keypad, size(for player), random for the dot
when it hits the player and some sprites for the game. This does not include the backdrop to set the
color background. There's a score count feature to where when player touches the sqaure it adds + 1 
to the score.

Player speed is controlled by `SPEED`.

Player and treasure sizes are conrolled by `PLAYER_SIZE` and `TREASURE_SIZE`.

Display boundaries are recored in `MIN_Y`,`MAX_Y`,`MIN_X`,and `MAX_X`.

`player` is at `(-50, 50)` and `treasure` is at `(0, 0)` for the starting positions.

## Planning required changes
1. Change the speed of the player

2. Change the backdrop color

3. Change the starting position of the player and dot, making new static constexpr for starting X and Y of each

4. Make it so when the player hits start, the game restarts (the player and treasure are sent back to their initial positions and the score is reset to zero)

5. Make it so that the player loops around the screen (if they go off the left of the screen, they show up on the right, if they go off the bottom of the screen they show up at the top, etc.)

6. Make a speed boost. When the player presses 'A', their speed is increased for a short amount of time. They can only use the speed boost 3 times. They get all speed boosts back when the game is restarted by pressing start.

## Brainstorming game ideas

## Plan for implementing game

