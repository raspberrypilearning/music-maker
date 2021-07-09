## Change the sound

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">

</div>
<div>
 <video width="320" height="240" controls>
  <source src="images/step-4-demo.mp4" type="video/mp4">
  Add interaction so that you can choose what sound the instrument has
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

Add code within a `forever`{:class='block3control'} block, so that when the pick touches the different sprites, the instument being played is changed. For example:

```blocks3
when flag clicked
forever
if <touching (Guitar v) ?> then
set instrument to ((5) Electric Guitar v)
end
```
--- /task ---

