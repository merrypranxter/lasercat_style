# Anti-Drift Prompting

Prompt strategies to prevent drift when generating `laser_cat_style` images.

## Core principle

Prompts must actively prevent the default tendencies of image systems toward:
- Polish
- Realism
- Tastefulness
- Seamlessness

## Anti-drift keywords

### Preserve collage
- "rough cutout"
- "visible edges"
- "sticker-like"
- "assembled"
- "composited"
- "collage style"

### Preserve tackiness
- "tacky"
- "gaudy"
- "lowbrow"
- "campy"
- "excessive"
- "rainbow neon glow"

### Preserve internet energy
- "internet meme"
- "2010s internet"
- "repost culture"
- "meme-native"
- "internet trash"

### Preserve badness
- "correct badness"
- "rough"
- "crusty"
- "JPEG artifacts"
- "compression"
- "glow bleed"

### Prevent polish
- "not polished"
- "not realistic"
- "not seamless"
- "not refined"
- "not tasteful"

## Anti-drift prompt structure

```
[POSITIVE STYLE CUES] + [NEGATIVE ANTI-DRIFT CUES] + [SPECIFIC CONSTRAINTS]
```

### Example
```
Loaf cat on giant pizza in purple nebula, rainbow laser eyes, tacky glow, visible cutout edges, rough collage style, internet meme aesthetic, 2010s internet trash energy, NOT polished, NOT realistic, NOT seamless, NOT refined, NOT tasteful
```

## Branch-specific anti-drift

### Food cat anti-drift
- "absurd scale"
- "food as throne"
- "cosmic junk food"
- NOT "food photography"
- NOT "realistic"

### Laser cat anti-drift
- "fake epic"
- "absurd power"
- "cat idiocy"
- NOT "sci-fi illustration"
- NOT "cinematic"

### Giant cat anti-drift
- "kaiju camp"
- "fake apocalypse"
- "absurd majesty"
- NOT "serious monster movie"
- NOT "realistic destruction"

### Drug cat anti-drift
- "chemically blasted"
- "posterized"
- "internet trash"
- NOT "visionary art"
- NOT "spiritual"

## Common drift triggers to avoid

### Words that cause polished drift
- "beautiful"
- "elegant"
- "refined"
- "masterpiece"
- "high quality"
- "detailed"
- "realistic"

### Words that cause serious drift
- "epic"
- "dramatic"
- "powerful"
- "majestic" (without "fake" or "absurd")
- "godlike" (without irony)

### Words that cause cute drift
- "cute"
- "adorable"
- "kawaii"
- "sweet"
- "lovely"

### Words that cause cool drift
- "cool"
- "stylish"
- "sleek"
- "modern"
- "design"

## Anti-drift negative prompts

```
NOT polished, NOT realistic, NOT seamless, NOT refined, NOT tasteful, NOT elegant, NOT beautiful, NOT high quality, NOT detailed, NOT cinematic, NOT serious, NOT kawaii, NOT cute, NOT cool, NOT stylish, NOT modern
```

## Testing for drift

After generation, check:
- Is the cat central?
- Is there visible collage?
- Is the tone absurd?
- Is there tackiness?
- Is there correct badness?

If any check fails, add more anti-drift cues.

## Related files
- `prompt_formula_short.md`
- `prompt_formula_long.md`
- `core_prompt_templates.md`
