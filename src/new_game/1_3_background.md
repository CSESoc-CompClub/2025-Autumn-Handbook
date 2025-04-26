# Task 1.3: Add Background Image

Now it’s time to make your game look cooler by adding a background!

Instead of just showing a black screen, let’s add an image behind everything.

## Step 1: Get all the images!

We need to load all the images that we need for our game!

1. Download the images onto our computer. Go to
https://www.girlsprogramming.network/flappy-bird-images and download all the images there.

2. Double click on the zip folder to unzip the the folder to get to the images

3. Move the images folder into the “flappy_bird” folder
---

## Step 2: Load the Background Image

Now you need to **load** the background image into your game.

```Hint:
- Use `pygame.image.load(...)`
- Save the result into a variable called something like `background`
```

You can first save the image path as a **variable**:

```
Hint:
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
