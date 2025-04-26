# Task 3.3: Initialise Active Foods List

1. Create a new empty list called `active_foods`, this list will store all the Food objects you create.
2. Write a `for` loop that goes through every item in your `foods` dictionary. In each loop, you will create a new Food object.
  ### Hint:
  - Use `.items()` to loop through both the **key** and **value**.
  - The key will be the **name** of the food.
  - The value will be a list containing:
    - `[image path, x position, y position]`

3. Create a New Food Object for Each Item
    ### Hint:
      - `key` -> name
      - `value[0]` -> image path
      - `value[1]` -> x position
      - `value[2]` -> y position


---

# Checkpoints

- [ ] An empty `active_foods` list created

- [ ] A loop that:
    - Goes through every food in your dictionary
    - Creates a Food object
    - Adds it into the active_foods list