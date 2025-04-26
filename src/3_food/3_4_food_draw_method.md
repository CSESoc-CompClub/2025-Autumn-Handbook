# Task 3.4: Create Food Draw Method

1.  Create a new method called `draw`.

### Hint:
- Use the `def` keyword.
- It should be written **inside** your Food class (at the same indentation level as `__init__()`).
- This method **won’t take any arguments** (only `self`).
- This method will **draw the food** onto the screen.

---

2. Draw the Sprite Onto the Screen
### Hint
- Use `screen.blit(...)` to draw.
- The first thing you want to draw is the **sprite** (image).
- The position to draw at is `(position_x, position_y)`.
```
---

# Checkpoints

- [ ] A `draw()` method inside your Food class which knows how to:
    - Draw the sprite
    - And place it at the correct position
