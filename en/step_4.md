## Jump into the air

Make Pico move upwards when the player presses the space bar.

<h2 class="c-project-heading--explainer">What you need to do</h2>

Add a new script with a `when space key pressed`{:class="block3events"} block and a `glide () secs to x: () y: ()`{:class="block3motion"} block.

![Pico sprite.](images/Pico-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
when [space v] key pressed
glide (0.3) secs to x: (-100) y: (80)
```

## Now run your code

Press the space bar.

Pico glides upwards and stays in the air. You'll make it land in the next step.
