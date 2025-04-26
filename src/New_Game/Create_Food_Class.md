# Task 3.1: Create a Food Class

In this task, you will create a **Food class** that acts as a blueprint for the food items (or anything else!) in your game.

Every Food will have:
- A name
- An image
- A sprite
- A position on the screen

---

## Step 1: Define the Food Class

Start by creating a new class called `Food`.

```
Hint:
- Remember to use the `class` keyword.
- Your class name should start with a **capital letter**.
```

Example:

```python
class Food:
```

## Step 2: Create the `__init__()` Method

Inside your `Food` class, create a special function called `__init__`.

```
Hints:
- Use the `def` keyword to define the method.
- The `__init__` method should accept **4 inputs**:
  - `name`
  - `image`
  - `position_x`
  - `position_y`
- Save each of these inputs into the object using `self.`
```

This means:
- The food remembers its name
- The food knows where it appears
- The food remembers which image to load

---

## Step 3: Set a Default Size

Still inside your `__init__()` method, set a default **size** for your food.

```
Hint:
- Create a new variable for size.
- Use a tuple like `(50, 50)` for width and height.
- Save it inside the object using `self.size`.
```
---

## Step 4: Load and Scale the Sprite

Still inside the `__init__()` method:

```
 Hints:
- Load the image file using Pygame's `image load` function.
- Scale the loaded image to the correct size using Pygame's `transform scale` function.
- Save the final scaled image into the object (e.g., `self.sprite`).
```

This way, every food item will have:
- A properly loaded picture
- A size that fits the screen

---

# Checkpoints

- [ ] A `Food` class (or a class of things you want to have)

- [ ] An `__init__()` method that:
    - Saves the name, image, and position
    - Sets a default size
    - Loads and scales the sprite

- [ ] A ready-to-use object for your game!