# Blank Screen — Theme Selector

A minimalist blank screen with 20 selectable themes from a dropdown.

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
| 8 | Aurora Mesh | **dynamic gradient** (CSS mesh — drifting radial blobs) |
| 9 | Prism Shift | **dynamic gradient** (hue-rotating linear gradient) |
| 10 | Liquid Canvas | **dynamic gradient** (canvas-driven flowing color blobs) |
| 11 | Plasma Interference | **dynamic · math** — superposition of travelling sine waves + Euclidean ring waves + phase fold |
| 12 | Fractal Flow | **dynamic · math** — 5-octave fbm fields, one field warping the other, breathing luminance |
| 13 | Domain Warp | **dynamic · math** — classic recursive domain warping (q1→q2→q3) |
| 14 | Voronoi Drift | **dynamic · math** — orbiting cell seeds, distance shading, cell-edge ridges, hashed hues |
| 15 | Metaballs | **dynamic · math** — iso-surface of 8 inverse-square potential fields on multi-frequency orbits |
| 16 | Ripple Interference | **dynamic · math** — expanding ring waves from Lissajous-travelling sources, 1/(1+d²) damping |
| 17 | Aurora Curtains | **dynamic · math** — 4 phase-locked sine curtains with field wobble + fbm turbulence |
| 18 | Reaction-Diffusion | **dynamic · math** — Gray–Scott model (A+2B→3B, B→∅) on a 160×90 grid with 5-point laplacian |
| 19 | Julia Drift | **dynamic · math** — escape-time iteration z←z²+c, drifting c parameter + slow zoom |
| 20 | Orbital Harmonics | **dynamic · math** — 7 golden-angle lights on 3-harmonic epicycles, additive gaussian falloff |

All math engines render per-pixel into a 240×135 buffer (shader-style) upscaled smooth to full screen.

- Choice persisted in `localStorage`.
- Honors `prefers-reduced-motion` (one static frame per theme) and pauses when the tab is hidden.

## Deploy

GitHub Pages — live at: https://msadique4871.github.io/blank-themes/