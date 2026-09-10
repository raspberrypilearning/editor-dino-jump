## Stop after a collision

![Dinosaur5.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

In **Dinosaur5**'s movement loop, add an `if then`{:class="block3control"} block with a `touching ()`{:class="block3sensing"} condition.

Choose **Pico** in the dropdown. Put `stop all`{:class="block3control"} inside the `if`{:class="block3control"} block.

```blocks3
when I start as a clone
show
repeat until <(x position) < (-230)>
    next costume
    change x by (-5)
+    if <touching (Pico v)?> then
        stop [all v]
    end
end
delete this clone
```

## Tip

The `touching ()`{:class="block3sensing"} block starts with **mouse-pointer** selected. Click its dropdown arrow and change this to **Pico**.

## Now run your code

Click the green flag and let a **Dinosaur5** clone reach **Pico**. The game should stop when they touch.

Restart and try jumping over a clone. The game should keep running when **Pico** clears it.
