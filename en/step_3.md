## Set the starting position

Make your character start every game in the same place.

Click on your character sprite, then click the `Code`{:class="block3control"} tab.

Add a script to show the character, place it near the ground, point it right, and set its size.

```blocks3
when green flag clicked
show
go to x: (-100) y: (-70)
point in direction (90)
set size to (100) %
```

These values suit Pico and make up your **starting state**. Clicking the green flag resets them before each game. Adjust the starting position, direction, and size until you're happy with how your sprite looks. A different sprite or backdrop may need different values.

## Now run your code

Click the green flag a few times.

Your character returns to the same starting position each time.
