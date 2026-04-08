# Cheap Glow and Halo Simulation

Efficient glow and halo effects for `laser_cat_style`.

## Glow types

### Bloom glow
- Brightness threshold
- Blur pass
- Additive blend

### Halo glow
- Expand silhouette
- Radial gradient
- Color tint

### Edge glow
- Detect edges
- Outward blur
- Intensity falloff

## Cheap techniques

### Single-pass blur
- Box blur approximation
- Few samples
- Acceptable quality

### Pre-blurred textures
- Glow baked in
- Larger texture
- Fast rendering

### Alpha expansion
- Scale alpha channel
- Color overlay
- No blur needed

### Dithered glow
- Noise-based falloff
- Fewer samples
- Visual noise acceptable

## Shader implementation

### Fragment shader glow
```glsl
vec4 glow = vec4(0.0);
for (int i = 0; i < SAMPLES; i++) {
    vec2 offset = samples[i] * glow_radius;
    glow += texture2D(tex, uv + offset);
}
glow /= float(SAMPLES);
```

### Parameters
- glow_radius: float
- glow_intensity: float
- glow_color: vec3
- glow_threshold: float

## Performance tips

- Reduce samples for speed
- Use lower resolution for glow
- Bake glow into textures
- Limit glow objects

## Related files
- `shader_behavior_overview.md`
- `beam_and_emission_behaviors.md`
