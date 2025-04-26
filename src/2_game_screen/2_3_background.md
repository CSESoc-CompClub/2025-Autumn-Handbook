# Task 1.3: Add Background Image
1. First save the image path as a **variable**: e.g.`background_image = "images/background/wooden_floor.jpeg"`
2. Then load it using `pygame.image.load(background_image)`
3. make sure the background **fits** the window Use `pygame.transform.scale(...)`
4. **draw the background** onto the screen use `screen.blit(...)`
---
# Checkpoints
- [ ] A `background_image` variable (path to the image)
- [ ] A `background` variable (the scaled loaded image)
- [ ] A `screen.blit(variable, coordinate)` line inside your `while running:` loop
- [ ] A background showing up instead of a black screen!