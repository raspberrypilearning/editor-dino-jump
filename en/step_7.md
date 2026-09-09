## Create obstacle clones

Use clones to make a stream of obstacles.

<h2 class="c-project-heading--explainer">What you need to do</h2>

## Step 1

**Create the clones**

Add a `forever`{:class="block3control"} loop to the end of the obstacle's script.

Inside the loop, create a clone and wait for one second before making the next one.

## Step 2

**Hide the original sprite**

Add a `hide`{:class="block3looks"} block before the loop, so that only the clones appear in the game.

![Dinosaur5 sprite.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
when green flag clicked
set size to (25) %
go to x: (280) y: (-85)
+hide
+forever
create clone of (myself v)
wait (1) seconds
end
```

A clone is a copy of a sprite. Each clone starts hidden, because the original obstacle is hidden.

## Now run your code

Click the green flag.

The original obstacle disappears from the Stage. Clones are being created, but you cannot see them yet.
