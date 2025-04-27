# Task 4.5: Draw Active Foods in Game Loop

Now that each Food knows how to draw itself, it's time to actually **draw all the food** onto your game window during the game!

1. Draw each active food item onto the screen by looping through all active foods inside your `while running:` game loop.
<br>
<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>💡 Hint</b></p>
    <ul>  
        <li>Create a loop inside your <code>while running:</code> loop to iterate over the <code>active_foods</code> list.</li>
        <li>Call the food’s <code>draw()</code> method.</li>
    </ul>
</div>

2. Check whether the player has interacted with the food. 
<br>
<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>💡 Hint</b></p>
    <ul>  
        <li>Inside the <code>for</code> loop:</li>
        <ul>
            <li>Use the player's method to check for interaction with the food.</li>
        </ul>
    </ul>
</div>
<br>
<div style="font-size: 20px; background-color: #d9d0f3; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>🚩 Checkpoint</b></p>
    <ul>  
        <li>A <code>for</code> loop inside the main game loop.</li>
        <li>You can interact with the food.</li>
        <li>All food is drawn onto the screen.</li>
        <li>All your food is visible.</li>
    </ul>
</div>