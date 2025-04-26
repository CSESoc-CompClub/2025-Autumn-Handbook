# Task 4.1 Create a hitbox for both the players and the foods

1. Create a property called ``interact_foods(self, food)`` in the food class
2. Use the colliderect to check whether the rectangular hitboxes are colliding 
3. If they are colliding, remove food from the active_foods list

```python
# Collision is True is the hitboxes are colliding and False if not
collision = self.hitbox.colliderect(food.hitbox) 
```