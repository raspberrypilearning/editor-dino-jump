## Add a collision sound

Play a sound when an obstacle catches Pico.

Click on the `Dinosaur5`{:class="block3looks"} sprite, then open the `Sounds`{:class="block3sound"} tab.

`Dinosaur5` already includes the `bite`{:class="block3sound"} sound. You can use it, or choose a different collision sound.

![The Sounds tab at the top-left of the Scratch editor.](images/sounds_tab.png)

Add a `play sound () until done`{:class="block3sound"} block inside the collision check, before `stop all`{:class="block3control"}.

![Dinosaur5 sprite.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

```blocks3
if <touching (Pico v)?> then
+play sound (bite v) until done
stop [all v]
end
```

## Now run your code

Click the green flag and let an obstacle catch Pico.

Your collision sound plays until it finishes, then the game stops.
