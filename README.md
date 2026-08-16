# Blank Screen — Gemini Aurora Collection

A minimalist blank screen with 12 flowing gradient themes, all colored
exclusively with Google Gemini's 4 signature colors:

- **Blue** `#4285F4` (`66,133,244`)
- **Green** `#34A853` (`52,168,83`)
- **Yellow** `#F9AB00` (`249,171,0`)
- **Red** `#EA4335` (`234,67,53`)

Every theme shares one continuous 4-stop cyclic palette (blue → green →
yellow → red → blue, linear lerp between stops — no banding, no hard edges)
and differs only by the math driving its motion:

| Theme | Motion |
|---|---|
| Aurora Curtains | layered sine curtains + fbm turbulence |
| Flowing Bands | travelling sine bands, lazy sway |
| Orbit Spin | gradient rotating inside a rotating frame |
| Galaxy Spiral | cut-free spiral sweep around a soft dark core |
| Radial Rings | soft concentric pulses from center |
| Diagonal Sheen | light sweeping across glass |
| Soft Breath | slow luminance breathing |
| Rain Ripples | three drifting wave sources |
| Morph Field | two folded sine grids crossing |
| Tidal Drift | slow horizontal tide with vertical swell |
| Center Pulse | radial heartbeat from the middle |
| Whirl Curtains | Aurora Curtains inside Orbit's rotating frame, rippled by drifting drops |

Rendered per-pixel at 240×135 shader-style, upscaled with smoothing. Honors
`prefers-reduced-motion` (one static frame) and pauses when the tab is hidden.

## Deploy

GitHub Pages — live at: https://msadique4871.github.io/blank-themes/