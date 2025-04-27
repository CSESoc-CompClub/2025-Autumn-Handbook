# Task 6.3: Show the score on the screen

1. Render the score on the screen. We can use `font.render()`.
2. `blit` the text onto the screen. Experiment with where you would put the score!

<div style="font-size: 20px; background-color: #ffebdf; color: black; padding: 15px; border-radius:10px;">
<p style="text-align: center;"><b>💡 Hint</b><p>
<ul>
    <li>Setting fonts and colours in pygame:</li>
    <pre><code>
colour = (256, 256, 256) # (R,G,B)
font = pygame.font.SysFont('Palatino', 50)
    </code></pre>
    <li>Rendering text. We concatenate "Score: " and the score variable to make it nice!</li>
    <li><a href="https://www.pygame.org/docs/ref/font.html#pygame.font.Font.render">Link to documentation for font.render</a></li>
    <pre><code>
score_render = font.render("Score: " + score, True, colour)
    </code></pre>
</ul>
</div>


