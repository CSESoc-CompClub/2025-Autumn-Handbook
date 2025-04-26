# Task 2.2: Create Game Loop

Now that you have set up your screen, you need to make sure the window stays open!

Without a special piece of code, your game window will open **for less than a second** and then immediately **close**!

To keep your game running, you need a **loop** that keeps checking:
- Is the game still open?
- Did the player click the close (X) button?

---

## Step 1: Create a \"Running\" Variable

First, you need a variable that ley Python check: Should the game keep running?

```
Hint:  
Use a variable called **`running`** and set it to **True** at the start
```
---

## Step 2: Build a Loop

Then you need a **while** loop.

``` Hint:
- It should say something like `while running:` 
- This means "**keep looping while the game is running**".
```
---

## Step 3: Handle Player Events

Inside your `while running:` loop,  
you need to **check what the player is doing**.

```Hint:
- Use `for event in pygame.event.get():`
- Go through all the events (like mouse clicks, window close, etc.)
- If the player close the game (event.type == pygame.QUIT`), you need to **stop the loop**!
```
---

## Step 4: Update the Screen Every Frame

At the end of your while loop,  refresh the screen:


### Hint:
- Use `pygame.display.update()`

---

# Checkpoints
- [ ] No crashing! Your window should stay open until you click the X!
- [ ] You should see something like this:
    ![black game window](../images/game_window/1.png)