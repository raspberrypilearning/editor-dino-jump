## Add a collision sound

Play a sound when an obstacle catches the character.

![Dinosaur5 sprite.](images/Dinosaur5-a.png){:width="100px" height="100px" style="object-fit: contain;"}

Click on your obstacle sprite, then open the `Sounds`{:class="block3sound"} tab.

`Dinosaur5` already includes the `bite`{:class="block3sound"} sound. You can use it, or choose a different collision sound.

![The Sounds tab at the top-left of the Scratch editor.](images/sounds_tab.png)

Add a `start sound ()`{:class="block3sound"} block inside the collision check, before `hide`{:class="block3looks"}.

```blocks3
if <touching (Pico v)?> then
+start sound (bite v)
hide
stop [all v]
end
```

## Now run your code

Click the green flag and let an obstacle catch your character.

Your collision sound starts before the game stops.
