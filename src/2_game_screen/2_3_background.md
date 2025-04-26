# Task 2.3: Add Background Image
1. Save the image path as a **variable**: e.g.`background_image = "images/background/wooden_floor.jpeg"`
2. Then load it using `pygame.image.load(background_image)`
3. Make sure the background **fits** the window Use `pygame.transform.scale(...)`
4. **draw the background** onto the screen use `screen.blit(...)`

<br>
<div style="font-size: 20px; background-color: #d9d0f3; color: black; padding: 15px; border-radius:10px;">
    <p style="text-align: center;"><b>🚩 Checkpoint</b><p>
    <ul>  
        <li>A <code>background_image</code> variable (path to the image)</li>
        <li>A <code>background</code> variable (the scaled loaded image)</li>
        <li>A <code>screen.blit(variable, coordinate)</code> line inside your <code>while running:</code> loop</li>
        <li>A background showing up instead of a black screen!</li>
    </ul>
</div>