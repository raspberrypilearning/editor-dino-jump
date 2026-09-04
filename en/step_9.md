## Randomise the gaps

Obstacles that appear at different times make the game less predictable.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

In the obstacle's `forever`{:class="block3control"} loop, replace the second `wait () seconds`{:class="block3control"} block with one that contains a `pick random () to ()`{:class="block3operators"} block.

```blocks3
forever
create clone of (myself v)
+wait (pick random (0.8) to (2.4)) seconds
end
```

## Now run your code

Click the green flag and watch when each obstacle appears.

The first clone still appears after one second. After that, clones appear at random intervals between the two numbers you chose.
