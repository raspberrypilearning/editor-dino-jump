## Land the jump

Bring your character back to the ground to finish the jump.

![Pico sprite.](images/Pico-a.png)

Add another `glide () secs to x: () y: ()`{:class="block3motion"} block to the bottom of the space-key script.

Use the character's starting `x` and `y` positions as its destination.

```blocks3
when [space v] key pressed
glide (0.3) secs to x: (-100) y: (80)
+glide (0.7) secs to x: (-100) y: (-70)
```

You will need to adjust the glide times and the height of the jump. Try different numbers until your sprite jumps the way you want it to.

## Now run your code

Press the space bar.

Your character jumps up and lands back in the same place.
