
--- question ---

---
legend: Vraag 2 van 3
---

Hier is een `Mijn blokken`{:class='block3myblocks'} definitie.

```blocks3
define play note: (note) beats (beats) rest (rest)
play note (note) for (beats) beats
rest for (rest) beats
```

Welke van de volgende blokken zouden `middelste C` afspelen voor `0.25` beats en een rust van `0.5` beats?

--- choices ---

- (x)

```blocks3
play note: (60) beats (0.25) rest (0.5)::custom
```

  --- feedback ---

  Ja, de midi-waarde '60' speelt de toon 'centrale C' voor 0.25 beats, en dan rust het instrument voor 0.5 beats.

  --- /feedback ---

- ( )
```blocks3
play note: (50) beats (0.25) rest (0.25)::custom
```

  --- feedback ---

  De lengte van de noot hier is correct, maar controleer wat de noot '50' speelt, en zorg ervoor dat je rust lang genoeg is.

  --- /feedback ---

- ( )
```blocks3
play note: (60) beats (0.25) rest (0.25)::custom
```

  --- feedback ---

De midi-waarde '60' speelt de toon 'centrale C' voor 0.25 beats, en vervolgens rust het instrument voor 0,25 beats. De rusttijd komt echter niet overeen met de vraag.

  --- /feedback ---

- ( )
```blocks3
play note: (60) beats (0.5) rest (0.25)::custom
```

  --- feedback ---

  Je hebt de juiste noot (midi waarde '60') voor 'centrale C' en de juiste hoeveelheid rust, maar het instrument zal de noot te lang afspelen.

  --- /feedback ---

--- /choices ---

--- /question ---
