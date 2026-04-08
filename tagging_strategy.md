# Tagging Strategy

Tagging system for classifying and filtering `laser_cat_style` content.

## Tag categories

### Core tags
- laser_cat_style
- cat_collage
- internet_meme
- cosmic_cat
- absurd_cat

### Motif tags
- laser_eyes
- rainbow_puke
- cosmic_food
- pizza_cat
- burger_cat
- fries_cat
- ufo_cat
- glam_cat
- diamond_cat
- sunglasses_cat

### Substyle tags
- cosmic_food_cat
- laser_cat
- psychedelic_cat
- drug_cat
- space_collage_cat
- monster_cat
- god_cat
- giant_cat
- glam_trash_cat
- household_object_cat

### Composition tags
- sticker_scatter
- single_gag_hero
- threat_tableau
- object_merge
- ride_scene

### Effect tags
- glow
- aura
- beam
- rainbow
- neon
- sparkle
- glitter

### Background tags
- galaxy
- nebula
- gradient
- void
- city
- apocalypse
- beach

### Tone tags
- absurd
- campy
- fake_epic
- dumb_delight
- tacky
- internet_trash

### Artifact tags
- rough_cutout
- glow_halo
- jpeg_crust
- compression
- correct_badness

## Tag hierarchy

```
laser_cat_style (root)
├── substyle
│   ├── cosmic_food
│   ├── laser_psychedelic
│   ├── space_collage
│   └── monster_god
├── motif
│   ├── food
│   ├── glam
│   ├── sci-fi
│   └── household
├── composition
│   ├── sticker_scatter
│   └── single_gag_hero
└── effect
    ├── laser
    ├── rainbow
    └── glow
```

## Search and filter

### Filter by substyle
Show only cosmic_food_cat images

### Filter by motif
Show only images with pizza

### Filter by composition
Show only sticker scatter mode

### Filter by effect
Show only laser eye images

### Combined filters
Show only cosmic_food_cat with laser eyes in sticker scatter mode

## Auto-tagging

### Detection
- Cat presence (ML model)
- Laser eyes (color pattern)
- Food items (object detection)
- Galaxy background (texture analysis)

### Confidence scores
- 0.0-1.0 for each tag
- Threshold for inclusion
- Manual review for low confidence

## Related files
- `style_dimensions.md`
- `generation_pipeline_notes.md`
