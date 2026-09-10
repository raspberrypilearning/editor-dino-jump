## Remove old clones

![Dinosaur5.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

On **Dinosaur5**, add `delete this clone`{:class="block3control"} **below** the movement loop, outside it.

```blocks3
when I start as a clone
show
repeat until <(x position) < (-230)>
    change x by (-5)
end
+delete this clone
```

## Tip

Use `-230`, not `-240`. Scratch keeps a little of each sprite on the Stage, so a small clone can get stuck before its `x position`{:class="block3motion"} reaches `-240`.

## Now run your code

Click the green flag to clear the old clones and start again.

Watch several **Dinosaur5** clones cross the Stage. Each should disappear near the left edge, with none left behind.
