# Scene Builder Templates

Modular templates for building custom `laser_cat_style` scenes.

## Modular formula

```
[CAT MODULE] + [OBJECT MODULE] + [EFFECT MODULE] + [BACKGROUND MODULE] + [STYLE MODULE]
```

---

## CAT MODULE

### Pose
- loaf (throne, deity)
- upright (humanoid, witness)
- sprawled (merge, relaxed)
- mid-action (ride, attack)
- face-forward (laser, emission)

### Expression
- blank (deity/idiot contrast)
- confused (absurd victim)
- smug (diva, entitled)
- feral (destroyer, action)
- screaming (rainbow puke, freakout)

### Scale
- tiny (witness, accent)
- medium (hero, standard)
- large (focal, dominant)
- giant (kaiju, god)

---

## OBJECT MODULE

### Food (1-3 items)
- pizza, burger, fries, taco, sandwich, bread, donut, milkshake

### Glam (1-3 items)
- sunglasses, diamonds, jewelry, hats, tiaras

### Sci-fi (1-2 items)
- UFO, planet, star, cosmic debris

### Household (1-2 items)
- toilet paper, box, furniture item

### Co-star (0-1 item)
- shark, dog, unicorn, alpaca, bird

---

## EFFECT MODULE

### Eye effects
- laser beams (red, rainbow)
- glowing eyes (neon, geometric)
- normal (no effect)

### Mouth effects
- rainbow puke
- sparkle stream
- normal (no effect)

### Body effects
- aura glow
- halo
- normal (no effect)

### Environmental effects
- particle scatter
- glow bleed
- normal (no effect)

---

## BACKGROUND MODULE

### Cosmic
- purple nebula
- blue galaxy
- green stellar field
- rainbow cosmic cloud

### Gradient
- rainbow gradient
- neon gradient (pink/cyan)
- sunset gradient
- black to color

### Scene
- grayscale city
- apocalypse clouds
- beach
- black void

---

## STYLE MODULE

### Composition
- sticker scatter
- single-gag hero
- threat tableau

### Artifact level
- crusty (high artifact)
- medium (some roughness)
- clean (minimal artifact)

### Tone
- absurd camp
- fake epic
- dumb delight

---

## Example builds

### Build 1: Classic Food Throne
```
CAT: loaf, blank, medium
OBJECT: burger (throne), fries (scatter)
EFFECT: none
BACKGROUND: purple nebula
STYLE: single-gag hero, medium, absurd camp
```

### Build 2: Laser Destroyer
```
CAT: face-forward, smug, giant
OBJECT: none (pure cat)
EFFECT: rainbow laser eyes
BACKGROUND: grayscale city
STYLE: threat tableau, medium, fake epic
```

### Build 3: Scatter Chaos
```
CAT: upright, confused, medium
OBJECT: pizza, diamonds, UFO, milkshake
EFFECT: aura glow
BACKGROUND: rainbow gradient
STYLE: sticker scatter, crusty, absurd camp
```

### Build 4: Ride Adventure
```
CAT: mid-action, feral, medium
OBJECT: shark (mount)
EFFECT: rainbow trail
BACKGROUND: blue galaxy
STYLE: single-gag hero, medium, dumb delight
```

### Build 5: Glam Diva
```
CAT: loaf, smug, medium
OBJECT: sunglasses, diamonds, jewelry
EFFECT: halo glow
BACKGROUND: pink nebula
STYLE: sticker scatter, clean, absurd camp
```

---

## Randomizer table

Roll or select randomly for procedural generation:

| d6 | Cat Pose | Expression | Object Type | Background | Effect |
|---|---|---|---|---|---|
| 1 | loaf | blank | food | nebula | laser eyes |
| 2 | upright | confused | glam | gradient | rainbow puke |
| 3 | sprawled | smug | sci-fi | city | aura |
| 4 | mid-action | feral | household | void | halo |
| 5 | face-forward | screaming | co-star | beach | glow |
| 6 | giant | goblin | mixed | apocalypse | particles |

---

## Related files
- `core_prompt_templates.md`
- `substyle_prompt_templates.md`
