## Score avoided obstacles

Award one point whenever an obstacle passes the character safely.

![Dinosaur5 sprite.](images/Dinosaur5-a.png)

In the clone script, add `change score by ()`{:class="block3variables"} after the movement loop and before `delete this clone`{:class="block3control"}.

```blocks3
when I start as a clone
show
repeat until <(x position) < (-200)>
next costume
change x by (speed)
if <touching (Pico v)?> then
start sound (bite v)
hide
stop [all v]
end
end
+change [score v] by (1)
delete this clone
```

The new block only runs after an obstacle reaches the left side without touching the character.

## Now run your code

Click the green flag and jump over an obstacle.

Your score goes up by one when the obstacle leaves the Stage.
