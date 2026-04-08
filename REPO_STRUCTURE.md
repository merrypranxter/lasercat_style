# REPO_STRUCTURE

This file explains the structure of the `laser_cat_style` repo and what each directory is for.

The repo is designed to support:
- human study
- AI prompting
- generative art systems
- shader translation
- app integration
- drift prevention
- machine-readable style logic

The overall philosophy is:

> define the style clearly
> break its behavior into parts
> formalize those parts for reuse
> prevent drift into generic slop

---

# Top-level files

## `README.md`
Primary introduction to the style and the repo.

## `REPO_STRUCTURE.md`
This file. Structural map and navigation aid.

---

# Directory map

## `01_overview/`
High-level identity files.

Purpose:
- define the style
- place it in internet culture context
- distinguish it from adjacent styles
- establish major substyle branches

Files:
- `style_definition.md`
- `internet_context.md`
- `neighboring_styles.md`
- `substyle_branches.md`

---

## `02_core_visual_dna/`
The core visual behavior layer.

Purpose:
- define what kinds of cats belong
- explain pose, crop, and collage behavior
- establish composition logic
- define scale absurdity
- classify cat power roles

Files:
- `cat_subject_logic.md`
- `pose_expression_and_crop_types.md`
- `collage_logic.md`
- `composition_modes.md`
- `absurd_scale_logic.md`
- `cat_power_roles.md`

---

## `03_motifs_and_objects/`
Motif and object library.

Purpose:
- formalize recurring visual ingredients
- preserve recognizable motif branches
- support prompt and app systems

Files:
- `laser_eyes.md`
- `rainbow_puke_and_emissions.md`
- `psychedelic_eyes_and_drug_cat.md`
- `cosmic_food_cat.md`
- `ufo_and_scifi_intrusions.md`
- `glam_trash_and_accessories.md`
- `household_object_nonsense.md`
- `other_animals_and_co_stars.md`
- `giant_cat_attack_and_godcat.md`

---

## `04_backgrounds/`
Background taxonomy.

Purpose:
- classify recurring backdrop families
- distinguish cosmic fields from collage scenes
- explain how background choice affects gag strength

Files:
- `nebula_galaxy_fields.md`
- `flat_gradient_meme_fields.md`
- `black_void_stage.md`
- `city_apocalypse_and_collage_scenes.md`
- `background_contrast_rules.md`

---

## `05_color_texture_and_artifacts/`
The crust layer.

Purpose:
- define palette families
- explain neon/rainbow logic
- document glow, blur, masking, compression, and correct ugliness
- prevent over-polishing

Files:
- `palette_system.md`
- `rainbow_and_neon_logic.md`
- `glow_blur_and_aura_behavior.md`
- `cutout_edges_and_masking_halos.md`
- `jpeg_crust_noise_and_resolution.md`
- `acceptable_ugliness.md`
- `polished_vs_correctly_bad.md`

---

## `06_tone_humor_and_scene_engineering/`
Tone and joke engine.

Purpose:
- explain why the images are funny
- differentiate scatter mode from hero-gag mode
- define deity-vs-idiot cat duality
- manage randomness without losing style identity

Files:
- `tone_definition.md`
- `humor_engines.md`
- `sticker_scatter_mode.md`
- `single_gag_hero_mode.md`
- `cat_as_deity_cat_as_idiot.md`
- `randomness_vs_repeatability.md`
- `scene_archetypes.md`

---

## `07_drift_control/`
Anti-drift firewall.

Purpose:
- protect the style from becoming generic
- identify common failure modes
- define allowed stylistic variants
- provide diagnostics and repair strategies

Files:
- `anti_drift.md`
- `what_this_style_is_not.md`
- `common_failure_modes.md`
- `allowed_variant_zone.md`
- `neighboring_style_confusions.md`
- `diagnostic_checklist.md`
- `repair_strategies.md`

---

## `08_prompt_system/`
Human-usable and AI-usable prompt layer.

Purpose:
- translate style analysis into prompt logic
- provide short and long formulas
- support branch-specific generation
- reinforce anti-drift prompting

Files:
- `prompt_formula_short.md`
- `prompt_formula_long.md`
- `core_prompt_templates.md`
- `substyle_prompt_templates.md`
- `scene_builder_templates.md`
- `anti_drift_prompting.md`

---

## `09_shader_and_genart_translation/`
Procedural translation layer.

Purpose:
- convert visual logic into generative rules
- simulate beams, glows, cutouts, object scatter, and collage depth
- support interactive visuals and algorithmic composition

Files:
- `shader_behavior_overview.md`
- `beam_and_emission_behaviors.md`
- `cutout_sprite_layer_simulation.md`
- `cheap_glow_and_halo_simulation.md`
- `floating_object_scatter.md`
- `collage_depth_flatness.md`
- `generative_cat_scene_logic.md`

---

## `10_app_integration/`
Tooling and UI layer.

Purpose:
- define style dimensions and knobs
- create tagging and filter logic
- support app pipelines and feature design

Files:
- `style_dimensions.md`
- `tagging_strategy.md`
- `ui_controls_and_knobs.md`
- `generation_pipeline_notes.md`

---

## `11_structured_data/`
Machine-readable style data.

Purpose:
- expose style rules in structured form
- support search, tagging, generation, and classification
- make the repo useful to software and agents

Files:
- `style_spec.json`
- `motif_library.json`
- `palette_presets.json`
- `artifact_behaviors.json`
- `scene_archetypes.json`
- `prompt_knobs.json`
- `neighboring_styles.csv`

---

## `12_examples/`
Ground-truth examples and recipes.

Purpose:
- show how the style behaves in practice
- compare branches
- illustrate drift and correction
- provide reusable prompt recipes

Files:
- `example_breakdowns.md`
- `substyle_examples.md`
- `drift_examples.md`
- `prompt_recipes.md`

---

# Suggested authoring order

Recommended drafting order:
1. `README.md`
2. `01_overview/*`
3. `02_core_visual_dna/*`
4. `06_tone_humor_and_scene_engineering/*`
5. `07_drift_control/*`
6. `03_motifs_and_objects/*`
7. `04_backgrounds/*`
8. `05_color_texture_and_artifacts/*`
9. `08_prompt_system/*`
10. `09_shader_and_genart_translation/*`
11. `10_app_integration/*`
12. `11_structured_data/*`
13. `12_examples/*`

Reason:
the overview, DNA, tone, and drift files define the style's identity before the repo branches into implementation details.

---

# Structural principles

This repo is organized around several assumptions:

## 1. The style has a real internal grammar
The repo does not treat the aesthetic as random meme trash.
It assumes repeatable logic.

## 2. Drift prevention is essential
Without anti-drift files, the style will quickly degrade into generic space cats or polished poster art.

## 3. Ugliness must be defined
A large part of the aesthetic depends on preserving the correct type of badness.

## 4. Prompting is not enough
The style also needs machine-readable specs, procedural logic, and application notes.

## 5. Humor is load-bearing
The image works because of joke structure, not just visual ingredients.

---

# Intended users

This structure is useful for:
- artists
- prompt engineers
- style system builders
- shader artists
- AI tool builders
- agent workflows
- repo-indexing systems
- future maintainers

---

# Maintenance philosophy

When expanding the repo:
- add files only when they define a real missing category
- avoid duplicating categories that belong in structured data
- update drift control whenever new style branches are added
- keep examples tied to real grammar, not just vibes
- preserve a strong distinction between core style and adjacent style overlap

---

# Final note

If this repo ever starts feeling too polished, too orderly, too tasteful, or too sane, something has gone wrong.

The structure should be rigorous.

The style itself should remain a colorful little asshole.
