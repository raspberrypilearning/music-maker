## Change the sound

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

</div>
<div>
 <video width="320" height="240" controls>
  <source src="images/step-4-demo.mp4" type="video/mp4">
  Add interaction so that you can choose what instrument is used when a sound is played.
</video>
</div>
</div>

The great thing about digital music is that you can get one sprite to easily play the sounds of many different instruments. 

--- task ---

Add some sprites to represent the different sounds you want your instrument to play. You can use instrument sprites, or choose whatever you like, it does not have to make sense.

![scratch stage with different instruments displayed, and a bunch of bananas](images/instuments.png)

--- /task ---

When the pick sprite touches your additional sprites, you can add code to the pick sprite to change the instrument that is being played. 

--- task ---

Add code within a `forever`{:class='block3control'} block, so that when the **pick** touches the different sprites, the instrument being played is changed. For example:

```blocks3
when flag clicked
forever
if <touching (Guitar v) ?> then
set instrument to (Electric Guitar v)
end
```
--- /task ---

You can customise your project to play any sound you want when the **pick** touches an instrument, object or character on the Stage. 

--- task ---

Add in some more ways to customise how your instrument sounds when it plays music.

--- /task ---

--- task ---

**Debug:** You might find some bugs in your project that you need to fix. Here are some common bugs.

--- collapse ---
---
title: The sound changes to the wrong sound
---

Make sure the if condition in your `Sensing`{:class='block3control'} block matches the instrument or sound you wanted from the `Music`{:class='block3custom'} extension.

```blocks3
when flag clicked
forever
+ if <touching (Guitar v) ?> then
+ set instrument to (Electric Guitar v)
end
```

--- /collapse ---

<mark> Would be grateful for some feedback on what bugs might go here.</mark>
- Something has happened to the sound
- I cannot hear the sound very well
- The instrument takes too long to change instrument/sound

--- /task ---
