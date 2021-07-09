## Invent an instrument

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
You will create a new sprite that will play sounds depending on where the user places their mouse pointer, or interacts with the scene.
</div>
<div>
 <video width="320" height="240" controls>
  <source src="step-2-demo.mp4" type="video/mp4">
  Your browser does not support mp4 video.
</video> 
</div>
</div>

--- task ---

Open a [new Scratch project](http://rpf.io/scratch-new){:target="_blank"}. Scratch will open in another browser tab.

[[[working-offline]]]

--- /task ---

Your instrument will play different notes, depending on the colours that make up the insturment sprite. You will need to choose what your instrument looks like. Do you want your instrument to look like a traditional instrument or something you see in your house or outside?

--- task ---

**Choose:** what your instrument looks like, and use the Paint Tool to create it. In the example below, the instrument looks like a flower. 

![a sprite shaped like a flower with petals of different colours](images/flower.svg)

Think about how many different sounds you want your instrument to play. Make sure your instrument has at least that many different colours.

--- /task ---

Your instrument will play notes when another sprite touches different colours on your instrument sprite. Just like a guitar will only play notes when a pick touches the strings, or a piano plays notes when fingers press on the keys.

--- task ---

Make or choose a Sprite that will follow your mouse pointer and be used to play different notes. In the example below, we have used a simple coloured circle.

![small gold circle sprite](images/pick.svg)

--- /task ---

Now, get your sprite to follow your mouse pointer, so that the person playing the instrument can control it.

--- task ---

Add code so that your new sprite follows the mouse pointer.

```blocks3
when flag clicked
forever
go to (mouse-pointer v)
```
--- /task ---

Use my blocks to design what your instrument sounds like.

<p style='border-left: solid; border-width:10px; border-color: #0faeb0; background-color: aliceblue; padding: 10px;'>Scratch uses what are called **midi** values to set the pitch of any note that is played. A **midi** value of `60` is the same as **middle C**. The higher the **midi** value, the higher the pitch of the note.
</p>


--- task ---

There are many elements of music that you can change. You can change the notes, instrument, beats, rest, and tempo.

Create a `My Blocks`{:class='block3myblocks'} that has inputs for as many of these elements as you think you will use.

--- collapse ---
---
title: Create a custom musical block
---


```blocks3
define play note: instrument (instrument) note (note) beats (beats) rest (rest)
set instrument to (instrument)
play note (note) for (beats) beats
rest for (rest) beats
```

--- /collapse ---

--- task ---

When the sprite 

--- /task ---


--- /task ---

**Debug:** You might find some bugs in your project that you need to fix. Here are some common bugs.

My instrument does not play anything when my sprite touches it

My instrument does not play one note after another

My instrument only plays one note

The music plays too quickly or too slow



--- /task ---

--- save ---

