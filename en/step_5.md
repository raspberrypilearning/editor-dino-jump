## Land the jump

Bring Pico back to the ground to finish the jump.

Add another `glide () secs to x: () y: ()`{:class="block3motion"} block to the bottom of the space-key script.

![Pico sprite.](images/Pico-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
when [space v] key pressed
glide (0.3) secs to x: (-100) y: (80)
+glide (0.7) secs to x: (-100) y: (-70)
```

## Now run your code

Press the space bar.

Pico jumps up and lands back in the same place.
