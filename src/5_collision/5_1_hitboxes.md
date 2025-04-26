# Task 5.1: Create a hitbox for both the players and the foods

1. Create an extra **property** in the player and food class. Use the .get_rect().move() function to create a rectangle that moves with the class' sprite.
2. Create a **method** called ``update(self)`` in the player class. Copy the property you just wrote into this method.
3. Call the player update method in the main game loop, just underneath ``player.draw()``

<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>💡 Hint</b><p>
    <ul style="width: 100%;">  
        <li><code>sprite.get_rect()</code> creates a rectangle the size of the image</li>
        <li><code>.move()</code> moves whatever it's attached to to an x and y coordinate</li>
        <li>To combine these into a hitbox you can have:
        <pre style="display: inline; font-size:80%;">self.hitbox = self.sprite.get_rect().move(self.position_x, self.position_y)</code></li>
    </ul>
</div>
