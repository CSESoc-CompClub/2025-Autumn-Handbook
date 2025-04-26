# Task 3.5: Draw Active Foods in Game Loop

Now that each Food knows how to draw itself, it's time to actually **draw all the food** onto your game window during the game!

- You will **loop through all active foods** inside your `while running:` game loop.


## Step 1: Loop Over `active_foods`

- Create a `for` loop inside your `while running:` loop which loop over the `active_foods` list.
- In each loop call the `draw()` method on the food to draw it on screen.
---

## Step 2: Drawing and Interaction
- Inside the `for` loop:
    - use player's method to check for interaction with the food.
    - call the food’s `.draw()` method.
---

# Checklist
- A `for` loop inside the main game loop
- You can interact with the food
- Draw the food onto the screen
- All your food are visible