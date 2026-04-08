# Generative Cat Scene Logic

Procedural generation of `laser_cat_style` scenes.

## Generation pipeline

### 1. Select composition mode
- Sticker scatter
- Single-gag hero
- Threat tableau

### 2. Select substyle branch
- Cosmic food cat
- Laser cat
- Giant cat
- etc.

### 3. Generate background
- Galaxy (noise-based)
- Gradient (color interpolation)
- Scene (city, beach)

### 4. Place cat
- Select from cat library
- Position centrally
- Apply pose/expression

### 5. Add objects
- Select from motif families
- Scatter or place strategically
- Apply scale variation

### 6. Add effects
- Lasers, glow, aura
- Particle systems
- Post-processing

### 7. Apply artifacts
- Cutout edges
- Glow bleed
- Compression simulation

## Randomization rules

### Cat selection
- Random from suitable pool
- Match substyle
- Ensure readability

### Object selection
- Random from motif families
- Minimum 1-2 objects
- Maximum 5-8 (avoid clutter)

### Color selection
- Random from palette family
- Ensure contrast
- Maintain saturation

### Scale selection
- Random within ranges
- Ensure hierarchy
- Avoid uniform sizing

## Constraints

### Cat centrality
- Cat must be visible
- Cat must be largest or central
- Cat must not be obscured

### Composition rules
- Follow mode guidelines
- Maintain hierarchy
- Ensure readability

### Anti-drift
- Check for polish
- Check for seriousness
- Check for cuteness drift

## Output validation

### Visual check
- Cat central?
- Readable?
- Absurd?

### Style check
- Correct motifs?
- Correct tone?
- Correct artifacts?

### Technical check
- No errors
- Performance acceptable
- Format correct

## Related files
- `shader_behavior_overview.md`
- `floating_object_scatter.md`
- `beam_and_emission_behaviors.md`
