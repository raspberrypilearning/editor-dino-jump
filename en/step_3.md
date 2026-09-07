## Set the starting position

Make your character start every game in the same place.

Click on your character sprite, then click the `Code`{:class="block3control"} tab.

Add a script to show the character and place it near the bottom-left of the Stage.

![Pico sprite.](images/Pico-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
when green flag clicked
show
go to x: (-100) y: (-70)
```

These values suit Pico. Adjust the `x` and `y` values if your character or backdrop is different.

## Now run your code

Click the green flag a few times.

Your character appears in the same starting position each time.
