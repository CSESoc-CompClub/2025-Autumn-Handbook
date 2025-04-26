# Task 4.1 Create a hitbox for both the players and the foods

1. Create an extra **property** in the player and food class. Use the .get_rect().move() function to create a rectangle that moves with the class' sprite.
2. Create a **method** called ``update(self)`` in the player class. Copy the property you just wrote into this method.
3. Call the player update method in the main game loop, just underneath ``player.draw()``

```python
# sprite.get_rect() creates a rectangle the size of the image
# .move() moves whatever it's attached to to an x and y coordinate
self.hitbox = self.sprite.get_rect().move(self.position_x, self.position_y)
```

