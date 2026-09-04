## Make the obstacle face left

Turn the obstacle so it faces towards the character.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

Add a `set rotation style ()`{:class="block3motion"} block and a `point in direction ()`{:class="block3motion"} block to the obstacle's setup script.

```blocks3
when green flag clicked
+set rotation style [left-right v]
set size to (25) %
go to x: (280) y: (-85)
+point in direction (-90)
```

The left-right rotation style keeps the obstacle upright when it points left.
