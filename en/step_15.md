## Move the obstacles

Move each clone across the Stage.

![Dinosaur5 sprite.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

In the clone script, add a `repeat until`{:class="block3control"} loop that checks whether the clone's `x position`{:class="block3motion"} is less than `-200`.

Inside the loop, change its x position by `speed`{:class="block3variables"}.

```blocks3
when I start as a clone
show
+repeat until <(x position) < (-200)>
change x by (speed)
end
```

## Now run your code

Click the green flag.

Each obstacle moves from right to left until it passes the character.
