# Task 1.3: Add Background Image

Now it’s time to make your game look cooler by adding a background!

Instead of just showing a black screen, let’s add an image behind everything.

## Step 1: Load the Background Image

First you need to **load** the background image into your game.
You can first save the image path as a **variable**:

```Hint:
- Something like `background_image = "images/background/wooden_floor.jpeg"`

- Then load it using `pygame.image.load(background_image)`
```
---

## Step 3: Scale the Background Image

Sometimes your background image won't match your screen size exactly.  
You want to make sure the background **fits** the window!

```
Hint:
- Use `pygame.transform.scale(...)`
- Resize the background to be `(screen_size_x, screen_size_y)`
```
---

## Step 4: Blit the Background onto the Screen

Finally, **draw the background** onto the screen.

``Hint:
- Use `screen.blit(...)`
- You want the background at the top-left corner `(0, 0)`
 ```

---

# Checkpoints

- [ ] A `background_image` variable (path to the image)

- [ ] A `background` variable (the scaled loaded image)

- [ ] A `screen.blit(variable, coordinate)` line inside your `while running:` loop

- [ ] A background showing up instead of a black screen!
