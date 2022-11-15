## Changer le son

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
Ajoute une interaction afin que tu puisses choisir quel instrument est utilisé lorsqu'un son est joué.
</div>
<div>
 <video width="320" height="240" controls>
  <source src="images/step-4-demo.mp4" type="video/mp4">
  Ton navigateur ne prend pas en charge le format de vidéo mp4.
</video>
</div>
</div>

Ce qu'il y a de bien avec la musique numérique, c'est que tu peux obtenir un sprite instrument pour jouer facilement les sons de nombreux instruments différents.

--- task ---

Ajoute quelques sprites pour représenter les différents sons que tu veux que ton instrument joue. Tu peux utiliser des sprites instruments ou choisir ce que tu veux, sans que cela ait un sens.

![scène Scratch avec différents instruments exposés, et un régime de bananes.](images/instruments.png)

--- /task ---

Tu peux ajouter du code au sprite **médiator** pour changer l'instrument qui est joué lorsque le sprite **prendre** touche tes sprites supplémentaires.

--- task ---

Ajoute du code dans un bloc `répéter indéfiniment`{:class='block3control'}, de sorte que lorsque le **médiator** touche les différents sprites, l'instrument joué change. Par exemple :

```blocks3
when flag clicked
forever
if <touching (Guitar v) ?> then
set instrument to (Electric Guitar v)
end
```
--- /task ---

Tu peux personnaliser ton projet pour jouer le son de ton choix lorsque le **médiator** touche un instrument, un objet ou un personnage sur la scène.

--- task ---

**Débogage :** Il est possible que tu trouves des bogues dans ton projet que tu dois corriger. Voici quelques bogues assez courants.

--- collapse ---
---
title : Le son passe au mauvais son
---

Assure-toi que la condition `si`{:class="block3control"} dans ton bloc `Capteurs`{:class='block3control'} correspond à l'instrument ou au son que tu veux de l'extension `Musique`{:class='block3custom'} .

```blocks3
when flag clicked
forever
+ if <touching (Guitar v) ?> then
+ set instrument to (Electric Guitar v)
end
```

--- /collapse ---

--- /task ---
