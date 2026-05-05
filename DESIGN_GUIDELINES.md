# Rukami Dark Paper Guidelines

- Use a dark paper direction: black surfaces, white ink, clean editorial structure, and flat accent blocks.
- Color tokens must live in `:root` and be reused everywhere. Do not create one-off opacity values in component CSS.
- Core tokens: surface `#050505`, surface-raised `#0B0B0D`, text `#F6F6F1`, inverse text `#050505`.
- Opacity tokens: `--ink-soft`, `--ink-muted`, `--ink-faint`, `--line`, `--line-soft`, `--paper-faint`, `--paper-soft`, `--scrim`, `--scrim-strong`, `--clear`.
- Accent colors are flat fills only: blue `#5C78FF`, red `#F23F43`, coral `#FF6853`, yellow `#FFDA53`, violet `#CA8EFF`, cyan `#45D1F4`.
- Readable text must be white on dark surfaces or black on accent/light surfaces.
- Do not use large white section backgrounds by default. White is for text, primary controls, or deliberate small paper cards with clear purpose.
- Do not use gradients, glows, shadows, text shadows, text strokes, or outline effects.
- Exception: edge fade gradients are allowed only as functional masks for horizontal carousels.
- Avoid colored readable text. Use accent colors for backgrounds, borders, controls, and non-text details.
- Decorative shapes should not be added on the live site until their placement is resolved in Figma.
- Real sticker-pack images may be rotated in small angles when used as a sticker-sheet composition.
- Use spacing from the 4/8/12/16/24/32 rhythm. Keep sections generous, but avoid empty scroll dead zones.
- Use 12-24px radii consistently. Avoid visually sharp blocks unless the whole section is intentionally editorial and aligned to the layout.
- Components need visible `:focus-visible` states, hover states, and clear disabled/error states when relevant.
- Copy should stay concise, confident, helpful, and human.
