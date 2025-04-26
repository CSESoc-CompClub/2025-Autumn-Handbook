# Task 3.1: Create a Player Class

1. We'll create a `Player` class to store: The player’s position, size and image (sprite)
<br>
<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>💡 Hint</b><p>
    <ul>  
        <li>Use the <code>class</code> keyword</li>
        <li>The class name should start with a <strong>capital letter</strong>.</li>
    </ul>
</div>


2. Inside your `Player` class, create an `__init__()` method.
<br>
<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>💡 Hint</b><p>
    <ul>  
        <li>Use the <code>def</code> keyword to define the method.</li>
        <li>The <code>__init__()</code> method should only have <code>self</code> as its input.</li>
    </ul>
</div>

3. Inside your `__init__()` method, create the following properties:
    - `position_x` -> set it to 0 for now
    - `position_y` ->set it to 0 for now
    - `size` -> (width, height) 
    - `image` -> file name 

4. Load and Scale the Player’s Sprite inside your `__init__()` method:
<br>
<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>💡 Hint</b><p>
    <ul>  
        <li>Use <code>pygame.image.load(...)</code> to load the player image file.</li>
        <li>Use <code>pygame.transform.scale(...)</code> to resize the player’s image to the correct size.</li>
    </ul>
</div>

---

# Checkpoints
<br>
<div style="font-size: 20px; background-color: #d9d0f3; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>🚩 Checkpoint</b></p>
    <ul>  
        <li>A <code>Player</code> class</li>
        <li>An <code>__init__()</code> method inside the class</li>
        <li>Player properties:</li>
        <ul>
            <li><code>position_x</code></li>
            <li><code>position_y</code></li>
            <li><code>size</code></li>
            <li><code>image</code></li>
            <li><code>sprite</code></li>
        </ul>
    </ul>
</div>