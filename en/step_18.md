## Detect a collision

Detect when an obstacle catches the character.

![Dinosaur5 sprite.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

Inside the clone's movement loop, add an `if then`{:class="block3control"} block that checks whether the obstacle is `touching ()`{:class="block3sensing"} your character.

If it is, hide the obstacle.

```blocks3
repeat until <(x position) < (-200)>
next costume
change x by (speed)
+if <touching (Pico v)?> then
hide
end
end
```

Choose your character's name from the `touching ()`{:class="block3sensing"} menu. The example uses `Pico`.

You'll stop the rest of the game after a collision in the next step.
