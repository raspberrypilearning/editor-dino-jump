## Stop after a collision

Stop the game when an obstacle touches the character.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

Add `stop all`{:class="block3control"} after the `hide`{:class="block3looks"} block inside the collision check.

```blocks3
if <touching (Pico v)?> then
hide
+stop [all v]
end
```

## Now run your code

Click the green flag and let an obstacle reach your character.

The game stops when they touch.
