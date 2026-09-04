## Reset the score

Make every game begin with a score of zero.

![Dinosaur5 sprite.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

In the obstacle's setup script, set `score`{:class="block3variables"} to `0` when the green flag is clicked.

```blocks3
when green flag clicked
set rotation style [left-right v]
set [speed v] to (-5)
+set [score v] to (0)
set size to (25) %
go to x: (280) y: (-85)
point in direction (-90)
hide
wait (1) seconds
forever
create clone of (myself v)
wait (pick random (0.8) to (2.4)) seconds
end
```

## Now run your code

Click the green flag. The score resets to `0`.
