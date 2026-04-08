# Shader Behavior Overview

Translating `laser_cat_style` into shader and generative art systems.

## Core principle

The style can be simulated procedurally using:
- Layer compositing
- Glow and bloom effects
- Particle systems
- Color manipulation
- Noise and distortion

## Key shader behaviors

### 1. Cutout layer simulation
- Alpha masking with rough edges
- Feathered borders
- Halo generation

### 2. Glow and bloom
- Brightness threshold bloom
- Color bleed
- Halo expansion

### 3. Beam and emission
- Ray marching for lasers
- Particle streams
- Trail rendering

### 4. Object scatter
- Particle systems
- Instanced rendering
- Random placement

### 5. Background fields
- Noise-based nebulae
- Star field generation
- Gradient interpolation

## Implementation approach

### Layer stack
1. Background (noise/gradient)
2. Cat sprite (masked texture)
3. Object sprites (instanced)
4. Effects (particles/glow)
5. Post-processing (bloom/color)

### Real-time considerations
- Glow is expensive, use sparingly
- Particle count affects performance
- Layer compositing can be batched

## Related files
- `beam_and_emission_behaviors.md`
- `cheap_glow_and_halo_simulation.md`
- `generative_cat_scene_logic.md`
