# Blank Screen — Theme Selector

A minimalist blank screen with 18 selectable themes from a dropdown.

## Themes

| # | Theme | Type |
|---|-------|------|
| 1 | Midnight | solid |
| 2 | Pure Black | solid |
| 3 | Slate | solid |
| 4 | Ivory | solid |
| 5 | Pure White | solid |
| 6 | Ocean | static gradient |
| 7 | Ember | static gradient |
| 8 | Aurora Curtains | **Gemini-style flowing aurora** (vertical sine curtains + fbm wobble) |
| 9 | Gemini Waves | **aurora** — pastel lavender/periwinkle/rose ribbon flow |
| 10 | Silk Ribbons | **aurora** — thin bright periwinkle ribbons, fast flow |
| 11 | Velvet Drape | **aurora** — slow deep purple folds with heavy turbulence |
| 12 | Candy Flow | **aurora** — cycling pastel spectrum ribbons |
| 13 | Neon Aurora | **aurora** — vivid electric blue/violet bands |
| 14 | Polaris Night | **aurora** — dark indigo, top-heavy glow |
| 15 | Boreal Glow | **aurora** — classic emerald green → teal northern lights |
| 16 | Sunrise Aurora | **aurora** — warm coral/orange/gold bands |
| 17 | Arctic Sheen | **aurora** — crisp icy cyan shimmer |
| 18 | Duotone Drift | **aurora** — alternating violet/teal two-tone bands |

All 11 aurora themes share one parameterized engine: per-pixel layered sine
ribbons with perpendicular wobble + fbm turbulence, rendered at 240×135 and
upscaled smooth (shader-style). Each variant is a distinct palette/motion config.

- Choice persisted in `localStorage`.
- Honors `prefers-reduced-motion` (one static frame per theme) and pauses when the tab is hidden.

## Deploy

GitHub Pages — live at: https://msadique4871.github.io/blank-themes/