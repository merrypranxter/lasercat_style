# Style Dimensions

Definable dimensions for `laser_cat_style` in app/UI systems.

## Core dimensions

### 1. Composition Mode
- sticker_scatter (0-1)
- single_gag_hero (0-1)
- threat_tableau (0-1)

### 2. Substyle Branch
- cosmic_food (0-1)
- laser_psychedelic (0-1)
- space_collage (0-1)
- monster_god (0-1)
- glam_trash (0-1)
- household_object (0-1)
- co_star (0-1)
- graphic_collage (0-1)

### 3. Cat Power Role
- deity (0-1)
- idiot (0-1)
- destroyer (0-1)
- witness (0-1)
- rider (0-1)
- throne_occupant (0-1)
- emission_source (0-1)

### 4. Visual Intensity
- low (minimal effects)
- medium (some effects)
- high (maximum effects)

### 5. Artifact Level
- crusty (high artifact)
- medium (some roughness)
- clean (minimal artifact)

### 6. Color Palette
- rainbow
- neon
- cosmic
- candy
- synthetic

### 7. Background Type
- galaxy
- gradient
- void
- city
- scene

### 8. Object Density
- sparse (1-2 objects)
- medium (3-5 objects)
- dense (6+ objects)

### 9. Scale Absurdity
- normal (realistic)
- exaggerated (somewhat wrong)
- absurd (very wrong)
- kaiju (extremely wrong)

### 10. Tone
- absurd
- campy
- fake_epic
- dumb_delight

## Dimension combinations

Example profile:
```json
{
  "composition": "sticker_scatter",
  "substyle": "cosmic_food",
  "cat_role": "throne_occupant",
  "intensity": "high",
  "artifact": "medium",
  "palette": "rainbow",
  "background": "galaxy",
  "object_density": "medium",
  "scale": "absurd",
  "tone": "dumb_delight"
}
```

## UI controls

### Sliders
- Intensity
- Artifact level
- Object density
- Scale absurdity

### Dropdowns
- Composition mode
- Substyle branch
- Cat role
- Color palette
- Background type

### Toggles
- Laser eyes
- Rainbow puke
- Glow effects
- UFO presence
- Glam accessories

## Related files
- `ui_controls_and_knobs.md`
- `generation_pipeline_notes.md`
