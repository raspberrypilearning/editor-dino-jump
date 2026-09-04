## Set the character's starting look

Make your character face the right way and start at a suitable size.

![Pico sprite.](images/Pico-a.png){:width="100px" height="100px" style="object-fit: contain;"}

Click on your character sprite.

Add a `point in direction ()`{:class="block3motion"} block and a `set size to () %`{:class="block3looks"} block to the character's starting script.

```blocks3
when green flag clicked
show
go to x: (-100) y: (-70)
+point in direction (90)
+set size to (100) %
```

Adjust the direction and size until your character looks right in its starting position.

## Now run your code

Click the green flag.

Your character starts in the position and at the size you chose. This position, direction, and size make up its **starting state**.
