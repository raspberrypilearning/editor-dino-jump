## Randomise the gaps

![Dinosaur5.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

In **Dinosaur5**'s `forever`{:class="block3control"} loop, put a `pick random () to ()`{:class="block3operators"} block inside `wait () seconds`{:class="block3control"}.

Use `1.2` and `2.4` to leave enough time between clones for **Pico** to land.

```blocks3
forever
    create clone of (myself v)
    wait (pick random (1.2) to (2.4)) seconds
end
```

## Now run your code

Click the green flag and watch several **Dinosaur5** clones appear.

The gaps should vary. Tap space to practise jumping over one clone at a time.
