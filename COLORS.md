# Letyar Color System

Letyar uses a restrained digital palette built around deep navy, electric cyan, and warm gold.

## Core palette

| Role | Hex | Usage |
|---|---|---|
| Deep Navy | `#0B1220` | Primary dark background, mark, navigation |
| Navy | `#101B33` | Surfaces, panels, secondary backgrounds |
| Electric Cyan | `#19D3E6` | Primary digital accent, links, interactive states |
| Warm Gold | `#E0B04B` | Craft / fingerprint highlight, graphic accents |
| White | `#F7FAFC` | Primary text on dark surfaces |
| Mist | `#CBD5E1` | Secondary text on dark surfaces |
| Slate | `#64748B` | Muted text / metadata |

## Heritage accent

| Role | Hex | Usage |
|---|---|---|
| Lacquer Red | `#B23A22` | Optional heritage / maker-signature accent |

Lacquer Red should not replace the core digital palette. It may appear in editorial or cultural brand contexts where the Myanmar lacquerware reference is intentional.

## Rules

- Deep Navy is the default dark foundation.
- Electric Cyan is the primary functional accent.
- Warm Gold is a visual highlight, not body text.
- Keep backgrounds mostly solid; avoid unnecessary gradients.
- Do not introduce new brand colors without updating this file first.

## CSS tokens

```css
:root {
  --letyar-ink: #0B1220;
  --letyar-navy: #101B33;
  --letyar-cyan: #19D3E6;
  --letyar-gold: #E0B04B;
  --letyar-white: #F7FAFC;
  --letyar-mist: #CBD5E1;
  --letyar-slate: #64748B;
  --letyar-lacquer: #B23A22;
}
```
