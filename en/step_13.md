## Detect a collision

End the game if an obstacle touches the character.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

Inside the clone's movement loop, add an `if then`{:class="block3control"} block that checks whether the obstacle is `touching ()`{:class="block3sensing"} your character.

If it is, hide the obstacle and `stop all`{:class="block3control"} scripts.

```blocks3
repeat until <(x position) < (-200)>
next costume
change x by (speed)
+if <touching (Pico v)?> then
hide
stop [all v]
end
end
```

Choose your character's name from the `touching ()`{:class="block3sensing"} menu. The example uses `Pico`.

## Now run your code

Click the green flag and let an obstacle reach your character.

The game stops when they touch.
