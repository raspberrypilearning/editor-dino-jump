## Land the jump

![Pico.](images/Pico-a.png){:width="100px" height="100px" style="object-fit: contain;"}

On **Pico**, add another `glide () secs to x: () y: ()`{:class="block3motion"} block to the bottom of the space-key script.

Use the same landing position as the green-flag script.

```blocks3
when [space v] key pressed
glide (0.3) secs to x: (-100) y: (80)
+glide (0.7) secs to x: (-100) y: (-70)
```

## Now run your code

Click the green flag, then tap the space bar once. **Pico** jumps up and lands at `y: -70`.

Wait for **Pico** to land before tapping space again.
