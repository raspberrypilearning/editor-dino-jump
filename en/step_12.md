## Stop after a collision

End the game when an obstacle catches Pico.

Inside the clone's movement loop, add an `if then`{:class="block3control"} block that checks whether the obstacle is `touching ()`{:class="block3sensing"} Pico.

If it is, stop all the scripts.

![Dinosaur5 sprite.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
repeat until <(x position) < (-240)>
next costume
change x by (-5)
+if <touching (Pico v)?> then
stop [all v]
end
end
```

## Now run your code

Click the green flag and let an obstacle reach Pico.

The game stops when they touch.
