## Move the obstacles

Move each clone across the Stage, then remove it when it has gone past the character.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

In the clone script, add a `repeat until`{:class="block3control"} loop that checks whether the clone's `x position`{:class="block3motion"} is less than `-200`.

Inside the loop, change its x position by `speed`{:class="block3variables"}.

After the loop, add `delete this clone`{:class="block3control"} so old clones do not build up.

```blocks3
when I start as a clone
show
+repeat until <(x position) < (-200)>
change x by (speed)
end
+delete this clone
```

## Now run your code

Click the green flag.

Obstacles move from right to left and disappear after passing the character.
