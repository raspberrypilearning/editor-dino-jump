## Animate the obstacles

Use the obstacle's costumes to animate it as it moves.

<h2 class="c-project-heading--explainer">What you need to do</h2>

Inside the clone's `repeat until`{:class="block3control"} loop, add a `next costume`{:class="block3looks"} block before the movement block.

![Dinosaur5 sprite.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
when I start as a clone
show
repeat until <(x position) < (-240)>
+next costume
change x by (-5)
end
delete this clone
```

## Now run your code

Click the green flag.

Each obstacle changes costume as it travels across the Stage.
