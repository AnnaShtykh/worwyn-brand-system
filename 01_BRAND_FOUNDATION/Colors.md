# Colors

The Worwyn palette is green-first: one vivid signature green carried by a family of deep and soft supporting tones. Surfaces are warm and papery, never sterile white.

## Core palette

| Color | Hex | RGB | Role |
|---|---|---|---|
| **Primary Green** | `#00993A` | 0, 153, 58 | The signature color. Logo mark, primary buttons, key highlights, bold backgrounds |
| **Dark Green** | `#006B2B` | 0, 107, 43 | Rich backgrounds, hover states, secondary emphasis |
| **Deep Green-Black** | `#001F0C` | 0, 31, 12 | Headline text, near-black backgrounds, premium surfaces |
| **Light Green Tint** | `#E7F5EA` | 231, 245, 234 | Soft section backgrounds, cards, subtle highlights |
| **Warm Beige** | `#E7E2DA` | 231, 226, 218 | Warm neutral surfaces, cards on off-white |
| **Off-White** | `#F7F5F2` | 247, 245, 242 | Default page/canvas background (instead of pure white) |

## Accent colors (confetti only)

These appear **only inside the confetti pattern** — as celebration sparks, never as primary UI or text colors:

| Color | Hex | Note |
|---|---|---|
| Amber | `#F1C278` | Warm confetti dots |
| Golden Yellow | `#F3C955` | Sparingly, smallest dots |
| Mint Teal | `#6FC7BB` | Cool counterpoint dots |

## How to combine

- **Default recipe:** Off-White `#F7F5F2` canvas → Deep Green-Black `#001F0C` text → Primary Green `#00993A` for the one thing that should pop.
- **Bold recipe:** Primary Green `#00993A` or Dark Green `#006B2B` canvas → Off-White text → silver logo mark.
- **Soft recipe:** Light Green Tint `#E7F5EA` or Warm Beige `#E7E2DA` canvas → Deep Green-Black text → Primary Green accents.
- Keep layouts **green-dominant with generous light breathing room** — roughly 60% light surface, 30% green, 10% accent is a good default.

## Accessible text pairings

| Background | Text color | Contrast | Verdict |
|---|---|---|---|
| Off-White `#F7F5F2` | Deep Green-Black `#001F0C` | ~17:1 | ✅ Any text size |
| Off-White `#F7F5F2` | Dark Green `#006B2B` | ~6.4:1 | ✅ Any text size |
| Off-White `#F7F5F2` | Primary Green `#00993A` | ~3.5:1 | ⚠️ Large text / headlines only |
| Primary Green `#00993A` | White / Off-White | ~4.3:1 | ✅ Headlines and UI text ≥18px |
| Dark Green `#006B2B` | Off-White `#F7F5F2` | ~6.1:1 | ✅ Any text size |
| Deep Green-Black `#001F0C` | Off-White `#F7F5F2` | ~16:1 | ✅ Any text size |

**Never:** pure black `#000000` text, pure white `#FFFFFF` full-bleed backgrounds (use Off-White), or accent amber/yellow/teal as text colors.
