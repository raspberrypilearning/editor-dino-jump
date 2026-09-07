## Stop after a collision

Stop the game when an obstacle touches the character.

Add `stop all`{:class="block3control"} after the `hide`{:class="block3looks"} block inside the collision check.

![Dinosaur5 sprite.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
if <touching (Pico v)?> then
hide
+stop [all v]
end
```

## Now run your code

Click the green flag and let an obstacle reach your character.

The game stops when they touch.
