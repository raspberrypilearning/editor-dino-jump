## Jump into the air

Make your character move upwards when the player presses the space bar.

Add a new script with a `when space key pressed`{:class="block3events"} block and a `glide () secs to x: () y: ()`{:class="block3motion"} block.

![Pico sprite.](images/Pico-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
when [space v] key pressed
glide (0.3) secs to x: (-100) y: (80)
```

Don't change the `x` value. Choose a higher `y` position for the top of the jump. Whatever your current `y` value is, add about `150` to it. (The example character starts at x: -100, y: -70 and jumps to y: 80.)

## Now run your code

Press the space bar.

Your character glides upwards and stays in the air. You'll make it land in the next step.
