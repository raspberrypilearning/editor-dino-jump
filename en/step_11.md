## Animate the clones

![Dinosaur5.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

In **Dinosaur5**'s clone script, add `next costume`{:class="block3looks"} inside the movement loop, before `change x by ()`{:class="block3motion"}.

```blocks3
when I start as a clone
show
repeat until <(x position) < (-230)>
+    next costume
    change x by (-5)
end
delete this clone
```

## Now run your code

Click the green flag. Each **Dinosaur5** clone changes costume as it moves and disappears near the left edge.

If any clones stay there and wiggle, check that the loop uses `-230` and that `delete this clone`{:class="block3control"} is below it.
