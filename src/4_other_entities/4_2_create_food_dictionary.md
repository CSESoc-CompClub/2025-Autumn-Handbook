# Task 4.2: Create a Food Dictionary
1. Create a dictionary called `foods`, this dictionary will hold all the food items you want to appear in your game.
<br>
<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>💡 Hint</b></p>
    <ul>  
        <li>Use curly braces <code>{}</code> to create a dictionary.</li>
        <li>Save it in your main code <strong>before</strong> your game loop starts.</li>
    </ul>
</div>
<br>
2. Inside your dictionary, add entries for each food you want
<br>
    <br>
<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>💡 Hint</b></p>
    <ul>  
        <li>Each <strong>key</strong> should be the name of the food (like <code>"banana"</code>, <code>"grapes"</code>, etc.).</li>
        <li>Each <strong>value</strong> should be a <strong>list</strong> that contains:</li>
        <ul>
            <li>The <strong>path</strong> to the image file.</li>
            <li>The <strong>x</strong> position.</li>
            <li>The <strong>y</strong> position.</li>
        </ul>
    </ul>
</div>

### Example structure:
```python
"food name": ["path/to/image.png", x_position, y_position]
```
