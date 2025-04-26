# Task 3.4: Create the move method

1. Inside your `Player` class, define a new method called `move()`.
    ### Hints:
        - Use the `def` keyword.
        - Remember to give it just one parameter: `self`.

2. Use `pygame.key.get_pressed()` to check which keys are currently being held down and save the result into a variable

3. Check if the player is pressing:
    | Key | Action |
    |:----|:-------|
    | `W` key | Move **up** |
    | `A` key | Move **left** |
    | `S` key | Move **down** |
    | `D` key | Move **right** |

    ### Hints:
    - If the `W` key is pressed, **decrease** the y position.
    - If the `S` key is pressed, **increase** the y position.
    - If the `A` key is pressed, **decrease** the x position.
    - If the `D` key is pressed, **increase** the x position.

4. change the player's image depending on the direction they are moving

    ### Hints:
        - When moving **up**, change the image to "poco_up.png"
        - When moving **down**, change the image to "poco_down.png"
        - When moving **left**, change the image to "poco_left.png"
        - When moving **right**, change the image to "poco_right.png"

# Checkpoints

- [ ] A `move()` method inside your Player class

- [ ] The method checks which keys are pressed

- [ ]The method updates the player’s `position_x` and `position_y`

- [ ] The player image changes when moving!