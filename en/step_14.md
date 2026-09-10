## Add a score

![Dinosaur5.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

## Step 1

With **Dinosaur5** selected, make a variable called `score`{:class="block3variables"}. Choose **For all sprites**.

![The Make a Variable button in the Variables menu.](images/make-a-variable.png)

Keep its checkbox ticked so it appears on the Stage.

![A ticked variable checkbox in the Variables menu.](images/variable-checkbox.png)

## Step 2

![Dinosaur5.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

In **Dinosaur5**'s setup script, set `score`{:class="block3variables"} to `0` when the green flag is clicked.

```blocks3
when green flag clicked
+set [score v] to (0)
set size to (25) %
go to x: (230) y: (-115)
hide
forever
    create clone of (myself v)
    wait (pick random (1.2) to (2.4)) seconds
end
```

## Now run your code

Click the green flag. The score appears on the Stage and resets to `0`.

It won't go up until you add the scoring block next.
