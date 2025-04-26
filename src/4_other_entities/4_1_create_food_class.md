# Task 4.1: Create a Food Class

1. Start by creating a new class called `Food`.
  Eg:
  ```python
  class Food:
  ```

2. Inside your `Food` class, create a special function called `__init__`.
  <br>
<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>💡 Hint</b></p>
    <ul>  
        <li>Use the <code>def</code> keyword to define the method.</li>
        <li>The <code>__init__</code> method should accept <strong>4 inputs</strong>:</li>
        <ul>
            <li><code>name</code></li>
            <li><code>image</code></li>
            <li><code>position_x</code></li>
            <li><code>position_y</code></li>
        </ul>
        <li>Save each of these inputs into the object using <code>self.</code></li>
    </ul>
</div>

3. Inside your `__init__()` method, set a default **size** for your food.
4. Still inside the `__init__()` method, load the image file using Pygame's `image.load` function.
5. Scale the loaded image to the correct size using Pygame's `transform scale` function.
6. Save the final scaled image into the object (e.g., `self.sprite`).

---
# Checkpoints
<br>
<div style="font-size: 20px; background-color: #d9d0f3; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>🚩 Checkpoint</b></p>
    <ul>  
        <li>A <code>Food</code> class (or a class of things you want to have).</li>
        <li>An <code>__init__()</code> method that:</li>
        <ul>
            <li>Saves the name, image, and position.</li>
            <li>Sets a default size.</li>
            <li>Loads and scales the sprite.</li>
        </ul>
        <li>A ready-to-use object for your game!</li>
    </ul>
</div>