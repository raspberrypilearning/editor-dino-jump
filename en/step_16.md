## Remove old obstacles

Delete each clone after it leaves the Stage so old obstacles do not build up.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

Add `delete this clone`{:class="block3control"} after the movement loop.

```blocks3
when I start as a clone
show
repeat until <(x position) < (-200)>
change x by (speed)
end
+delete this clone
```

The block runs after an obstacle has passed the left side of the Stage.
