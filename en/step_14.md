## Add a score

Make a score that the player can see, and reset it at the start of every game.

**Make the variable**

Make a new variable called `score`{:class="block3variables"}, **For all sprites**.

![The Make a Variable button in the Variables menu.](images/make-a-variable.png)

Keep its checkbox ticked, so the variable appears on the Stage.

![A ticked variable checkbox in the Variables menu.](images/variable-checkbox.png)

**Reset it at the start**

In the obstacle's setup script, set `score`{:class="block3variables"} to `0` when the green flag is clicked.

![Dinosaur5 sprite.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
when green flag clicked
+set [score v] to (0)
set size to (25) %
go to x: (280) y: (-85)
hide
forever
create clone of (myself v)
wait (pick random (0.8) to (2.4)) seconds
end
```

## Now run your code

Click the green flag.

The score appears on the Stage and resets to `0`.
