# Beam and Emission Behaviors

Procedural beam and emission effects for `laser_cat_style`.

## Laser beam types

### Straight beam
- Ray from point in direction
- Constant width or taper
- Color gradient along length

### Divergent beam
- Multiple rays from point
- Spreading angle
- Fan or cone distribution

### Rainbow beam
- Color cycling along length
- ROYGBIV sequence
- Prismatic effect

## Implementation techniques

### Ray marching
- Step along ray direction
- Accumulate color/intensity
- Add glow falloff

### Particle beams
- Stream of particles
- Velocity-based trails
- Fade over time

### Geometry beams
- Cylinder or cone mesh
- Gradient texture
- Additive blending

## Emission types

### Rainbow puke
- Particle fountain
- Color cycling
- Gravity-affected

### Sparkle stream
- Glitter particles
- Random sparkle
- Fade and respawn

### Aura glow
- Radial gradient
- Pulsing intensity
- Color cycling

## Shader parameters

```
beam_origin: vec2
beam_direction: vec2
beam_length: float
beam_width: float
beam_color: vec3
beam_intensity: float
glow_radius: float
glow_intensity: float
```

## Related files
- `shader_behavior_overview.md`
- `cheap_glow_and_halo_simulation.md`
