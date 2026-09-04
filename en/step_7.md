## Create obstacle clones

Use clones to make a stream of obstacles.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

Click on your obstacle sprite.

Hide the original obstacle and wait for one second. Then add a `forever`{:class="block3control"} loop that creates a clone and waits before making the next one.

```blocks3
when green flag clicked
set rotation style [left-right v]
set size to (25) %
go to x: (280) y: (-85)
point in direction (-90)
+hide
+wait (1) seconds
+forever
create clone of (myself v)
wait (1) seconds
end
```

A clone is a copy of a sprite. The original obstacle stays hidden so that only its copies appear.

The clones are hidden too at the moment. You'll show them in the next step.
