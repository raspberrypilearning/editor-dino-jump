## Move each obstacle

Make each new clone appear and travel across the Stage.

Start a new script on the obstacle sprite with a `when I start as a clone`{:class="block3control"} block.

Add a `show`{:class="block3looks"} block, then a `repeat until`{:class="block3control"} loop that checks whether the clone's `x position`{:class="block3motion"} is less than `-200`.

Inside the loop, change its x position by `-5`.

![Dinosaur5 sprite.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
when I start as a clone
show
repeat until <(x position) < (-200)>
change x by (-5)
end
```

A negative number in `change x by ()`{:class="block3motion"} moves the clone to the left.

## Now run your code

Click the green flag.

Each obstacle appears on the right and moves across the Stage towards Pico, then stops near the left edge.
