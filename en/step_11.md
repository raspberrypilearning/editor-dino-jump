## Create obstacle clones

Use clones to make a stream of obstacles.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

In the obstacle's setup script, wait for one second before starting a `forever`{:class="block3control"} loop.

Inside the loop, create a clone and wait for one second before making the next one.

```blocks3
when green flag clicked
set rotation style [left-right v]
set size to (25) %
go to x: (280) y: (-85)
point in direction (-90)
hide
+wait (1) seconds
+forever
create clone of (myself v)
wait (1) seconds
end
```

A clone is a copy of a sprite. Each clone starts hidden because the original obstacle is hidden.
