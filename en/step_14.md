## Set the obstacle speed

Store the movement speed in a variable so it is easy to change later.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

Make a new variable called `speed`{:class="block3variables"}, **For all sprites**.

Untick its checkbox to hide it from the player.

![The Make a Variable button in the Variables menu.](images/make-a-variable.png)

In the obstacle's setup script, set `speed`{:class="block3variables"} to `-5`.

```blocks3
when green flag clicked
set rotation style [left-right v]
+set [speed v] to (-5)
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

A negative speed will make the clones move to the left.
