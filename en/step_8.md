## Move each clone

![Dinosaur5.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

## Step 1

On **Dinosaur5**, start a new script with `when I start as a clone`{:class="block3control"} and `show`{:class="block3looks"}.

Add a `repeat until`{:class="block3control"} loop. Inside it, add `change x by ()`{:class="block3motion"} and set it to `-5`. Leave the condition empty for now.

```blocks3
when I start as a clone
show
repeat until <>
    change x by (-5)
end
```

## Step 2

![Dinosaur5.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

From **Operators**, drag a `less than`{:class="block3operators"} block into the loop's condition. Put `-230` in its right-hand slot.

```blocks3
<() < (-230)>
```

From **Motion**, put an `x position`{:class="block3motion"} block in the left-hand slot.

```blocks3
<(x position) < (-230)>
```

The finished script looks like this:

```blocks3
when I start as a clone
show
repeat until <(x position) < (-230)>
    change x by (-5)
end
```

## Tip

A negative number in `change x by ()`{:class="block3motion"} moves the clone to the left.

## Now run your code

Click the green flag. Each **Dinosaur5** clone appears on the right, moves towards **Pico** and stops near the left edge.

They will collect there for now. You'll remove them next.
