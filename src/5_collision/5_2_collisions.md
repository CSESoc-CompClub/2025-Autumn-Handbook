# Task 5.2: Check whether two hitboxes are colliding

1. Create a property called ``interact_foods(self, food)`` in the food class
2. Use the colliderect to check whether the rectangular hitboxes are colliding 
3. If they are colliding, remove food from the active_foods list

<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>💡 Hint</b><p>
    <ul style="width: 100%;">  
        <li> Check if the player hitbox is colliding with the food hitbox:<br>
        <code>collision = self.hitbox.colliderect(food.hitbox)</code>
        </li>
        <li>The collision variable is True if the hitboxes are colliding and False if not</li>
    </ul>
</div>