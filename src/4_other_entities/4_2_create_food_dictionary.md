# Task 3.2: Create a Food Dictionary
1. Create a dictionary called `foods`, this dictionary will hold all the food items you want to appear in your game.
    ### Hint:
    - Use curly braces `{}` to create a dictionary.
    - Save it in your main code **before** your game loop starts.
2. Inside your dictionary, add entries for each food you want
    - Each **key** should be the name of the food (like `"banana"`, `"grapes"`, etc.).
    - Each **value** should be a **list** that contains:
        - The **path** to the image file
        - The **x** position
        - The **y** position
    ### Hint for structure:
    ```python
    "food name": ["path/to/image.png", x_position, y_position]
    ```