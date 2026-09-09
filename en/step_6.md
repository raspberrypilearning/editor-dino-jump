## Add and position the obstacle

Create something for Pico to jump over.

<h2 class="c-project-heading--explainer">What you need to do</h2>

Click **Choose a Sprite**, then find `Dinosaur5`{:class="block3looks"} in the sprite library and click on it.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

Dinosaur5 has several costumes, so it can animate as it moves.

Click on the `Dinosaur5`{:class="block3looks"} sprite, then click the **Code** tab.

Add a script to set its size and position.

```blocks3
when green flag clicked
set size to (25) %
go to x: (280) y: (-85)
```

## Now run your code

Click the green flag.

The obstacle shrinks and moves to the right edge of the Stage, ready to travel towards Pico.
