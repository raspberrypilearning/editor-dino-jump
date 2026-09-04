## Set up the score

Keep track of how many obstacles the player avoids.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

Make a new variable called `score`{:class="block3variables"}, **For all sprites**.

Keep its checkbox ticked so the player can see it.

In the obstacle's setup script, set `score`{:class="block3variables"} to `0` when the green flag is clicked.

```blocks3
when green flag clicked
set rotation style [left-right v]
set [speed v] to (-5)
+set [score v] to (0)
set size to (25) %
go to x: (280) y: (-85)
point in direction (-90)
```

The score now resets at the start of every game. You'll award points in the next step.
