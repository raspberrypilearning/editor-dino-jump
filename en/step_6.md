## Add an obstacle

Create something for your character to jump over.

Choose any sprite to be an obstacle.

This example uses `Dinosaur5`{:class="block3looks"}, which has several costumes so it can animate as it moves.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

Click on your obstacle sprite, then click the `Code`{:class="block3control"} tab.

Add a script to set its rotation style, size, position, and direction.

```blocks3
when green flag clicked
set rotation style [left-right v]
set size to (25) %
go to x: (280) y: (-85)
point in direction (-90)
```

The example position puts the obstacle just beyond the right edge of the Stage. Change the `y` position if your obstacle does not sit on the ground.
