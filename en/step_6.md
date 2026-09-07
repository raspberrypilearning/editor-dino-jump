## Land the jump

Bring your character back to the ground to finish the jump.

Add another `glide () secs to x: () y: ()`{:class="block3motion"} block to the bottom of the space-key script.

Don't change the `x` and `y` values - they're already correct. The final `x` and `y` values must be the same as the character's starting position in the green flag script.

![Pico sprite.](images/Pico-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
when [space v] key pressed
glide (0.3) secs to x: (-100) y: (80)
+glide (0.7) secs to x: (-100) y: (-70)
```

Adjust the glide times and the height of the jump until your sprite jumps the way you want it to.

## Now run your code

Press the space bar.

Your character jumps up and lands back in the same place.
