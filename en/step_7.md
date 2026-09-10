## Create Dinosaur5 clones

![Dinosaur5.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

## Step 1

On **Dinosaur5**, add a `forever`{:class="block3control"} loop to the setup script. Inside it, create a clone and wait `1.5` seconds before making the next one.

```blocks3
when green flag clicked
set size to (25) %
go to x: (230) y: (-115)
+forever
    create clone of (myself v)
    wait (1.5) seconds
end
```

## Step 2

![Dinosaur5.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

Add `hide`{:class="block3looks"} before the loop to hide the original **Dinosaur5**.

```blocks3
when green flag clicked
set size to (25) %
go to x: (230) y: (-115)
+hide
forever
    create clone of (myself v)
    wait (1.5) seconds
end
```

## Tip

A clone is a copy of a sprite. These clones start hidden because they copy the hidden **Dinosaur5**.

## Now run your code

Click the green flag. **Dinosaur5** disappears. The clones are being created, but you'll make them visible in the next step.
