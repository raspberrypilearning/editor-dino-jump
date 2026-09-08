## Detect a collision

Detect when an obstacle catches Pico.

Inside the clone's movement loop, add an `if then`{:class="block3control"} block that checks whether the obstacle is `touching ()`{:class="block3sensing"} Pico.

If it is, hide the obstacle.

![Dinosaur5 sprite.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
repeat until <(x position) < (-200)>
next costume
change x by (-5)
+if <touching (Pico v)?> then
hide
end
end
```

Choose `Pico`{:class="block3looks"} from the `touching ()`{:class="block3sensing"} menu.

You'll stop the rest of the game after a collision in the next step.
