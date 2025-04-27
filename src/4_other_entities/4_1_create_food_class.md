# Task 4.1: Create a Food Class

1. Start by creating a new class called `Food`. This will be quite similar to the Player class.
  E.g.:
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
        <li>Your Food class should have more than 4 properties though, being <code>name</code>, <code>image</code>, <code>size</code>, <code>position_x</code>, <code>position_y</code> and <code>sprite</code></li>
        <li>Save each of these inputs into the object using <code>self.</code></li>
        <li>Note that you can set default values for a class like so:</li>
        <pre><code>
class Car:
    # Notice how we don't have a weight parameter in the 
    # brackets below.
    def __init__(self, colour, speed):
        # We can set this when creating an instance
        colour = colour
        speed = speed
        # Default property values
        weight = 20
        </code></pre>
    </ul>
</div>

3. Inside your `__init__()` method, set a default **size** for your food.
4. Still inside the `__init__()` method, load the image file using Pygame's `image.load` function.
5. Scale the loaded image to the correct size using Pygame's `transform scale` function.
6. Save the final scaled image into the object (e.g., `self.sprite`).

<br>
<div style="font-size: 20px; background-color: #d9d0f3; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>🚩 Checkpoint</b></p>
    <ul>  
        <li>A <code>Food</code> class (or a class of things you want to have).</li>
        <li>Code in the <code>__init__()</code> method that:</li>
        <ul>
            <li>Saves the name, image, and position.</li>
            <li>Sets a default size.</li>
            <li>Loads and scales the sprite.</li>
        </ul>
        <li>A ready-to-use object for your game!</li>
    </ul>
</div>