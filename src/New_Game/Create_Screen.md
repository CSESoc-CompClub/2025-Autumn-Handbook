# Task 1.1: Create Game Screen
Now that Pygame is ready, it’s time to make your game window!
## Step 1: Think About the Screen Size

When creating a game window, you need to decide:

- How wide should the screen be?
- How tall should the screen be?

Let's create **two variables** to store these numbers!

<span style="font-size: 20px;">Hint:</span>  
Use easy-to-remember names like **`screen_size_x`** and **`screen_size_y`**.

For example:
- `screen_size_x` could be **800** (pixels wide)
- `screen_size_y` could be **600** (pixels tall)

---

## Step 2: Set Up Your Game Window

Now that you have the screen size saved inside variables,  
you need to **tell Pygame to create a window** of that size.

Use the Pygame function that starts with `pygame.display.`...

There's a function that sounds like "**set mode**" — it’s the one you want!

---

### Your mission:

- Use `screen_size_x` and `screen_size_y`
- Use a Pygame function to **create the window**
- Save the result into a variable called `screen`

---
# YOU CANNOT SEE YOUR SCREEN YET

After Task 1.1, your file is **almost ready**,  
but you must **complete Task 1.2** first (the game loop)  
BEFORE YOU CAN SEE A SCREEN WHEN YOU RUN YOUR PYGAME!

Otherwise the window will crash immediately, AND YOU WON'T EVEN BE ABLE TO SEE IT!

---

# Checkpoint

- [ ] Two variables for width and height

- [ ] A screen object created using Pygame and your variables

- [ ] A clean setup without hard-coding numbers inside `set_mode`!


