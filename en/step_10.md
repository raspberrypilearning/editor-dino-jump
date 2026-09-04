## Hide the original obstacle

Hide the original obstacle so only its clones appear in the game.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

Add a `hide`{:class="block3looks"} block to the end of the obstacle's setup script.

```blocks3
when green flag clicked
set rotation style [left-right v]
set size to (25) %
go to x: (280) y: (-85)
point in direction (-90)
+hide
```

Click the green flag. The original obstacle disappears from the Stage.
