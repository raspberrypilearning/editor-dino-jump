## Jump into the air

Make your character move upwards when the player presses the space bar.

![Pico sprite.](images/Pico-a.png)

Add a new script with a `when space key pressed`{:class="block3events"} block and a `glide () secs to x: () y: ()`{:class="block3motion"} block.

```blocks3
when [space v] key pressed
glide (0.3) secs to x: (-100) y: (80)
```

Use the same `x` position as the character's starting position. Choose a higher `y` position for the top of the jump.

## Now run your code

Press the space bar.

Your character glides upwards and stays in the air. You'll make it land in the next step.
