# UI Controls and Knobs

UI control design for `laser_cat_style` generation apps.

## Control categories

### 1. Cat Controls

#### Cat selection
- Dropdown: cat library
- Random button
- Upload custom

#### Cat pose
- Dropdown: loaf, upright, sprawled, mid-action, face-forward
- Random button

#### Cat expression
- Dropdown: blank, confused, smug, feral, screaming
- Random button

#### Cat scale
- Slider: tiny to kaiju

### 2. Object Controls

#### Object selection
- Multi-select: food, glam, sci-fi, household, co-star
- Random button
- Clear all

#### Object density
- Slider: sparse to dense

#### Object scale
- Slider: accent to dominant

### 3. Effect Controls

#### Eye effect
- Dropdown: none, laser red, laser rainbow, glowing

#### Mouth effect
- Dropdown: none, rainbow puke, sparkle stream

#### Body effect
- Dropdown: none, aura, halo

#### Environmental effect
- Dropdown: none, particles, glow bleed

### 4. Background Controls

#### Background type
- Dropdown: galaxy, gradient, void, city, scene

#### Background color
- Color picker (for gradients)

#### Background intensity
- Slider: subtle to dramatic

### 5. Style Controls

#### Composition mode
- Dropdown: sticker scatter, single-gag hero, threat tableau

#### Artifact level
- Slider: clean to crusty

#### Color palette
- Dropdown: rainbow, neon, cosmic, candy, synthetic

#### Tone
- Dropdown: absurd, campy, fake epic, dumb delight

### 6. Preset Controls

#### Preset selection
- Dropdown: classic, laser destroyer, food throne, scatter chaos, glam diva

#### Save preset
- Button: save current settings

#### Randomize all
- Button: randomize all controls

## Control layout

```
┌─────────────────────────────────────┐
│  [Preview Area]                     │
├─────────────────────────────────────┤
│  CAT  │  OBJECTS  │  EFFECTS        │
├───────┼───────────┼─────────────────┤
│  BG   │  STYLE    │  PRESETS        │
├───────┴───────────┴─────────────────┤
│  [Generate]  [Randomize]  [Save]    │
└─────────────────────────────────────┘
```

## Advanced controls

### Seed input
- Text field for reproducibility

### Negative prompt
- Text area for anti-drift

### Batch size
- Slider: 1-10 images

### Quality
- Slider: draft to final

## Related files
- `style_dimensions.md`
- `generation_pipeline_notes.md`
