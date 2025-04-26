# Task 3.4: Create Food Draw Method

Now that you have your Food objects ready, we need a way to **draw** them onto the screen!

- We will add a `draw()` method inside the Food class, so each food knows **how to draw itself**.

## Step 1: Define a New Method Called `draw()`

- Inside your `Food` class,  
    create a new method called `draw`.
- This method **won’t take any arguments** (only `self`).
- This method will **draw the food** onto the screen.
```
 Hint:
- Use the `def` keyword.
- It should be written **inside** your Food class (at the same indentation level as `__init__()`).
```
---

## Step 2: Draw the Sprite Onto the Screen

- Inside your `draw()` method:

``` 
Hint:
- Use `screen.blit(...)` to draw.
- The first thing you want to draw is the **sprite** (image).
- The position to draw at is `(position_x, position_y)`.
```
---

# Checkpoints

- [ ] A `draw()` method inside your Food class which knows how to:
    - Draw the sprite
    - And place it at the correct position
