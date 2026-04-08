# Cutout Sprite Layer Simulation

Simulating collage cutout behavior with sprites and layers.

## Layer structure

```
Layer 0: Background
Layer 1: Large objects
Layer 2: Cat (main subject)
Layer 3: Small objects
Layer 4: Effects
Layer 5: Post-processing
```

## Sprite properties

### Position
- x, y coordinates
- z-depth for layering

### Scale
- Uniform or non-uniform
- Animated scaling

### Rotation
- Angle in degrees/radians
- Animated rotation

### Alpha
- Transparency
- Fade in/out

### Blend mode
- Normal
- Additive (for glow)
- Multiply (for shadows)

## Cutout edge simulation

### Rough edge
- Noise-based edge distortion
- Jitter along border
- Irregular outline

### Halo edge
- Outer glow
- Color fringing
- Expand alpha

### Feathered edge
- Gradient alpha falloff
- Soft transition
- Blur effect

## Implementation

### Sprite atlas
- Pack multiple sprites
- UV coordinate lookup
- Efficient rendering

### Instancing
- Same sprite, multiple positions
- Different transforms
- Single draw call

### Masking
- Alpha test for cutout
- Stencil for complex shapes
- Shader-based masking

## Related files
- `shader_behavior_overview.md`
- `collage_depth_flatness.md`
