# Task 4.3: Initialise Active Foods List

Now that you have a dictionary of food items, it's time to **create real Food objects** from that dictionary!

- We’ll create a list of active foods that can be drawn onto the screen later.

## Step 1: Create an Empty List

First, create a new empty list called `active_foods`, This list will store all the Food objects you create.

```
 Hint:
- Use square brackets `[]` to create an empty list.
- Save this list somewhere **before your game loop starts**.
```
---

## Step 2: Loop Over Your Foods Dictionary

Now write a `for` loop that goes through every item in your `foods` dictionary. In each loop, you will create a new Food object!

``` Hint:
- Use `.items()` to loop through both the **key** and **value**.
- The key will be the **name** of the food.
- The value will be a list containing:
  - `[image path, x position, y position]`
```
---

## Step 3: Create a New Food Object for Each Item

Inside your loop:
- Create a new `Food` object.
- Give it the correct **name**, **image**, **position_x**, and **position_y**.
- Add the new Food object into the `active_foods` list.

``` 
Hint:
- Use the key and value pieces carefully!
  - `key` -> name
  - `value[0]` -> image path
  - `value[1]` -> x position
  - `value[2]` -> y position
```

---

# Checkpoints

- [ ] An empty `active_foods` list created

- [ ] A loop that:
    - Goes through every food in your dictionary
    - Creates a Food object
    - Adds it into the active_foods list