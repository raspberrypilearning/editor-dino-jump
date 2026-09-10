## Score each successful jump

![Dinosaur5.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

In **Dinosaur5**'s clone script, add `change score by ()`{:class="block3variables"} **after** the movement loop and **before** `delete this clone`{:class="block3control"}.

```blocks3
when I start as a clone
show
repeat until <(x position) < (-230)>
    next costume
    change x by (-5)
    if <touching (Pico v)?> then
        play sound (bite v) until done
        stop [all v]
    end
end
+change [score v] by (1)
delete this clone
```

## Tip

The score only changes when a **Dinosaur5** clone reaches the left edge without touching **Pico**. It goes up a little after the jump, when the clone disappears.

## Now run your code

Click the green flag and jump over a clone. Watch it reach the left edge: `score`{:class="block3variables"} should go up by `1`.

Restart and let a clone hit **Pico**. You shouldn't earn a point for that clone.
