
--- question ---

---
legend: Question 2 sur 3
---

Voici une définition de `mes blocs`{:class='block3myblocks'}.

```blocks3
define play note: (note) beats (beats) rest (rest)
play note (note) for (beats) beats
rest for (rest) beats
```

Lequel des blocs suivants jouerait un `do médian` pendant `0,25` battement et un silence de `0,5` battement ?

--- choices ---

- (x)

```blocks3
play note: (60) beats (0.25) rest (0.5)::custom
```

  --- feedback ---

  Oui, la valeur midi '60' joue la note "do-médian" pendant 0.25 battement, puis l'instrument fait une pause pendant 0.5 battement.

  --- /feedback ---

- ( )
```blocks3
play note: (50) beats (0.25) rest (0.25)::custom
```

  --- feedback ---

  La longueur de la note ici est correcte, mais vérifie bien quelle note le nombre « 50 » joue et assure-toi que la pause est suffisamment longue.

  --- /feedback ---

- ( )
```blocks3
play note: (60) beats (0.25) rest (0.25)::custom
```

  --- feedback ---

La valeur midi '60' joue la note "do médian" pendant 0,25 battement, puis l'instrument fait une pause pendant 0,25 battement. Cependant, le temps de pause ne correspond pas à la question.

  --- /feedback ---

- ( )
```blocks3
play note: (60) beats (0.5) rest (0.25)::custom
```

  --- feedback ---

  Tu as la bonne note (valeur midi '60') pour 'do médian' et la bonne quantité de pause, cependant l'instrument jouera la note trop longtemps.

  --- /feedback ---

--- /choices ---

--- /question ---
