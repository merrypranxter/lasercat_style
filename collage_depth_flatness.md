# Collage Depth Flatness

Simulating the flat, layered look of digital collage.

## Core principle

`laser_cat_style` collage has:
- Minimal depth cues
- Clear layer separation
- Sticker-like flatness
- No realistic perspective

## Layer behavior

### No perspective
- Orthographic projection
- Parallel lines stay parallel
- No vanishing points

### Clear separation
- Distinct layers
- No soft depth transitions
- Hard edges between elements

### Scale = importance
- Larger = more important
- Not realistic distance
- Compositional hierarchy

## Implementation

### Orthographic camera
```
projectionMatrix = ortho(left, right, bottom, top, near, far);
```

### Layer sorting
- Back to front rendering
- Z-index based
- No depth testing

### Parallax (optional)
- Different scroll speeds
- Fake depth
- Not realistic perspective

## Depth cues to avoid

### Realistic perspective
- Vanishing points
- Foreshortening
- Atmospheric perspective

### 3D shading
- Complex lighting
- Cast shadows
- Ambient occlusion

### Depth of field
- Blur based on distance
- Realistic focus

## Acceptable depth

### Layer overlap
- Objects in front/behind
- Clear ordering
- Not realistic depth

### Scale variation
- Different sizes
- Not distance-based
- Compositional only

### Parallax scrolling
- Different speeds
- Fake depth
- 2.5D effect

## Related files
- `shader_behavior_overview.md`
- `cutout_sprite_layer_simulation.md`
