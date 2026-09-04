## Animate the obstacles

Use the obstacle's costumes to animate it as it moves.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

Inside the clone's `repeat until`{:class="block3control"} loop, add a `next costume`{:class="block3looks"} block before the movement block.

```blocks3
when I start as a clone
show
repeat until <(x position) < (-200)>
+next costume
change x by (speed)
end
delete this clone
```

## Now run your code

Click the green flag.

Each obstacle changes costume as it travels across the Stage.
