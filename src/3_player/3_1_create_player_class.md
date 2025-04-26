# Task 3.1: Create a Player Class

1. We'll create a `Player` class to store: The player’s position, size and image (sprite)
    ### Hint:
        - Use the `class` keyword.
        - The class name should start with a **capital letter**.


2. Inside your `Player` class, create an `__init__()` method.
    ### Hints:
        - Use the `def` keyword to define the method.
        - The `__init__()` method should only have `self` as its input.

3. Inside your `__init__()` method, create the following properties:
    - `position_x` -> set it to 0 for now
    - `position_y` ->set it to 0 for now
    - `size` -> (width, height) 
    - `image` -> file name 

4. Load and Scale the Player’s Sprite inside your `__init__()` method:
    ### Hints:
        - Use `pygame.image.load(...)` to load the player image file.
        - Use `pygame.transform.scale(...)` to resize the player’s image to the correct size.

---

# Checkpoints

- [ ] A `Player` class

- [ ] An `__init__()` method inside the class

- [ ] Player properties:
    - `position_x`
    - `position_y`
    - `size`
    - `image`
    - `sprite`
