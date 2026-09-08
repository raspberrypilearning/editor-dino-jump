## Remove old obstacles

Delete each clone after it reaches the left side, so old obstacles do not build up.

Add `delete this clone`{:class="block3control"} after the movement loop.

![Dinosaur5 sprite.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
when I start as a clone
show
repeat until <(x position) < (-200)>
change x by (-5)
end
+delete this clone
```

## Now run your code

Click the green flag.

Each obstacle disappears once it has passed Pico, instead of piling up on the left.
