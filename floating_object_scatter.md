# Floating Object Scatter

Procedural object scatter for sticker scatter mode.

## Scatter algorithm

### 1. Define scatter area
- Bounding box
- Density target
- Exclusion zones (cat area)

### 2. Generate positions
- Random or Poisson disk
- Minimum distance constraint
- Layer-based distribution

### 3. Assign objects
- Random from motif library
- Size-based placement
- Color coordination

### 4. Apply transforms
- Random rotation
- Random scale (within range)
- Depth sorting

## Parameters

```
scatter_count: int
scatter_area: vec4 (x, y, width, height)
min_distance: float
size_range: vec2 (min, max)
rotation_range: vec2 (min, max)
motif_library: array
```

## Distribution strategies

### Random scatter
- Pure random positions
- Fast but may cluster

### Poisson disk
- Even distribution
- Minimum distance
- More natural

### Grid-based
- Regular grid
- Random jitter
- Controlled density

### Layered
- Foreground layer
- Midground layer
- Background layer
- Different scales

## Animation

### Floating motion
- Sine wave drift
- Random velocity
- Rotation over time

### Parallax
- Different speeds per layer
- Depth illusion
- Scroll response

## Implementation

### CPU generation
- Pre-calculate positions
- Store in buffer
- Upload to GPU

### GPU instancing
- Single mesh
- Multiple transforms
- Efficient rendering

## Related files
- `shader_behavior_overview.md`
- `cutout_sprite_layer_simulation.md`
