# Task 3.1: Create a Food Class

1. Start by creating a new class called `Food`.
    ### Example:
    ```python
        class Food:
    ```

2. Inside your `Food` class, create a special function called `__init__`.
  ### Hints:
  - Use the `def` keyword to define the method.
  - The `__init__` method should accept **4 inputs**:
    - `name`
    - `image`
    - `position_x`
    - `position_y`
  - Save each of these inputs into the object using `self.`

3. Inside your `__init__()` method, set a default **size** for your food.
4. Still inside the `__init__()` method, load the image file using Pygame's `image load` function.
5. Scale the loaded image to the correct size using Pygame's `transform scale` function.
6. Save the final scaled image into the object (e.g., `self.sprite`).

---
# Checkpoints

- [ ] A `Food` class (or a class of things you want to have)

- [ ] An `__init__()` method that:
    - Saves the name, image, and position
    - Sets a default size
    - Loads and scales the sprite

- [ ] A ready-to-use object for your game!