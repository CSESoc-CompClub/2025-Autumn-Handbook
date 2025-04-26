# Task 5.2: Check whether two hitboxes are colliding

1. Create a property called ``interact_foods(self, food)`` in the food class
2. Use the colliderect to check whether the rectangular hitboxes are colliding 
3. If they are colliding, remove food from the active_foods list

### Hint
```python
# Collision is True is the hitboxes are colliding and False if not
collision = self.hitbox.colliderect(food.hitbox) 
```