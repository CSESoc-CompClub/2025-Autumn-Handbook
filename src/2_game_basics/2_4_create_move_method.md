# Task 2.4: Create the move method

Your task is to create the move method. 

___

## Task 2.4.1
First, you need to find whether a certain key is being pressed or not. Similar to yesterday, we can use a function called [`pygame.key.get_pressed()`](https://www.pygame.org/docs/ref/key.html#pygame.key.get_pressed). 

```
Hint: This returns a list of booleans.
For example, the return value may look something like this 
    -> [False, False, False, False, True, False, False]
```

How might we check whether the 7th key is pressed?

## Task 2.4.2
Secondly, we need to update the `position_x` and `position_y` variables of our player according to what key was pressed. 

For example, something like
```
if w is pressed
    move up
else if a is pressed
    move left
else if s is pressed
    move down
else 
    move right
```

## Task 2.4.3
Add `player.move()` and `player.draw()` to the game loop.


