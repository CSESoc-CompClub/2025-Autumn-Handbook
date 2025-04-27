# Task 4.3: Initialise Active Foods List
1. Create a new empty list called `active_foods`, and this list will store all the Food objects you create.
2. Write a `for` loop that goes through every item in your `foods` dictionary. In each loop, you will create a new Food object.

<br>
<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>💡 Hint</b></p>
    <ul>  
        <li>Use <code>.items()</code> to loop through both the <strong>key</strong> and <strong>value</strong>.</li>
        <li>The <strong>key</strong> will be the <strong>name</strong> of the food.</li>
        <li>The <strong>value</strong> will be a list containing:</li>
        <ul>
            <li><code>[image path, x position, y position]</code></li>
        </ul>
    </ul>
</div>
<br>
3. Create a New Food Object for Each Item
<br>
<br>
<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>💡 Hint</b></p>
    <ul>  
        <li><code>key</code> -> name</li>
        <li><code>value[0]</code> -> image path</li>
        <li><code>value[1]</code> -> x position</li>
        <li><code>value[2]</code> -> y position</li>
    </ul>
</div>
<br>
<div style="font-size: 20px; background-color: #d9d0f3; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>🚩 Checkpoint</b></p>
    <ul>  
        <li>An empty <code>active_foods</code> list is created.</li>
        <li>A loop that:</li>
        <ul>
            <li>Goes through every food in your dictionary.</li>
            <li>Creates a Food object.</li>
            <li>Adds it into the <code>active_foods</code> list.</li>
        </ul>
    </ul>
</div>