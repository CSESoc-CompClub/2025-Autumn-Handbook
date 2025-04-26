# Task 6.3: Show the score on the screen

1. Render the score on the screen. We can use `font.render()`.
2. `blit` the text onto the screen. Experiment with where you would put the score!

### Hints
```python
# Setting fonts in pygame
colour = (256, 256, 256) # (R,G,B)

# Creating text - concatenate "Score: " and the score variable
# https://www.pygame.org/docs/ref/font.html#pygame.font.Font.render
font.render("Score: " + score, True, colour)

# Drawing on the screen
screen.blit(image, (x_position, y_position))
```


