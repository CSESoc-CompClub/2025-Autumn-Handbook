# Task 2.2: Create Game Loop
1. Use a variable called `running` and set it to `True` at the start
2. Make a `while` loop which will keep looping while the game is running.
3. Inside your `while running:` loop, loop through each event type and check quit the game if the event type is quit. 
4. Inside your `while running:` loop, update the display

<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>💡 Hint</b><p>
    <ul>  
        <li>Make a for loop: <code>for event in pygame.event.get()</code></li>
        <li>If the player closes the game <code>event.type == pygame.QUIT</code>, you need to set a certain variable to False</li>
    </ul>
</div>

5. At the end of your while loop,  refresh the screen with `pygame.display.update()`

<div style="font-size: 20px; background-color: #d9d0f3; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>🚩 Checkpoint</b><p>
    <ul>  
        <li>No crashing! Your window should stay open until you click the X!</li>
        <li>You should see something like this:</li>
        <img src="../images/game_window/1.png"/>
    </ul>
</div>