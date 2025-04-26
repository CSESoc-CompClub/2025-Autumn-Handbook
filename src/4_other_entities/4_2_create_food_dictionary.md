# Task 4.2: Create a Food Dictionary

Now that we have a Food class ready, it's time to create a **dictionary** to store all the different food items!

A dictionary will let you:
- Store multiple foods easily
- Access their images and positions
- Organise your game's world neatly


## Step 1: Create an Empty Dictionary

Create a dictionary called `foods`, This dictionary will hold all the food items you want to appear in your game.

```
Hint:
- Use curly braces `{}` to create a dictionary.
- Save it in your main code **before** your game loop starts.
```

## Step 2: Add Food Items into the Dictionary

- Inside your dictionary, add entries for each food you want!

- Each **key** should be the name of the food (like `"banana"`, `"grapes"`, etc.).

- Each **value** should be a **list** that contains:
    - The **path** to the image file
    - The **x** position
    - The **y** position

```Hint for structure:

    ```python
        "food name": ["path/to/image.png", x_position, y_position]
    ```
```