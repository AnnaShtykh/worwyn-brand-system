# Visual Language

How Worwyn looks beyond the logo: composition, patterns, imagery, and ready-to-use image-generation prompts.

## The core look

**Folded paper, green energy, human warmth.** Imagine the brand as a physical desk: warm off-white paper surfaces, one vivid green origami object, occasional confetti from a celebration. Digital layouts should feel like that desk — tactile, calm, with one point of energy.

Principles:

1. **One focal point.** Every layout has exactly one hero: a headline, a photo, or the mark. Everything else supports it.
2. **Green-dominant, light-carried.** Roughly 60% light surface (off-white/beige/tint), 30% green, 10% accent. Full-green layouts are for bold moments only.
3. **Generous breathing room.** Wide margins (≥8% of canvas per side). If it feels empty, it's probably right.
4. **Geometry with soft edges.** Rounded-corner cards (24–48px radius on 1080px canvases), straight grids, no diagonal chaos.
5. **Paper depth, not effects.** Depth comes from the origami texture in the real assets — never add drop shadows, glows, bevels, or 3D effects to text or shapes.

## Composition

**Prefer:**

- asymmetric layouts
- generous negative space
- strong typographic hierarchy
- editorial image crops
- intentional visual tension

**Avoid:**

- centered everything
- equal-sized elements
- excessive borders
- random decorative shapes

Centered, symmetric layouts are the deliberate exception (e.g., a quote card), never the default. Build layouts like an editorial spread: a dominant element, an off-axis balance point, and space that's allowed to stay empty.

## Visual personality

**The brand should feel:**

- sophisticated
- editorial
- contemporary
- confident
- minimal

**The brand should NOT feel:**

- playful
- childish
- overly decorative
- generic
- overly corporate

The brand is warm, but warmth comes from language and photography — not from decoration. Confetti is a celebration *accent*, used sparingly at real milestone moments: a sophisticated wink, never a party theme.

## The three patterns (in `00_ASSETS/patterns/`)

| Pattern | File | Feeling | When to use |
|---|---|---|---|
| **W zigzag** | `pattern-w-zigzag-green.png` | Bold, rhythmic, confident | Story backgrounds, campaign covers, section dividers |
| **Confetti** | `pattern-confetti-offwhite.png` | Celebration, delight | Match announcements, new-hire stories, milestones, welcome posts |
| **W outline** | `pattern-w-outline-green.png` | Premium, quiet, crafted | Closing slides, stationery, "thank you" moments |

Rules: patterns are backgrounds, never foregrounds. Place text only on calm areas or on a solid block over the pattern. One pattern per layout, never two.

## Product UI style (from the real app & landing page)

Social and presentation visuals should feel like siblings of the product. Observed patterns from the shipped screens:

- **Headline highlight:** long headlines are deep green-black with the single key word in primary green ("You're **more** than a resume"). Use this device in hero headlines everywhere.
- **The Rise icon:** a green flame/leaf drop in a circle is the "Rise" (like) action; a double flame marks a Mutual Rise™. When showing product moments, use these icons — never a heart or thumbs-up.
- **Cards:** heavily rounded corners (~40–48px radius at app scale), full-bleed candid photography, role label + verification badge overlaid. Profile cards may tilt/rotate slightly for energy (landing page scatters them like dealt cards; one match screen rotates two cards into a "W" echo).
- **Buttons:** fully rounded pills. Primary = primary green fill, off-white text, optional leading icon. Secondary = beige/off-white fill, deep green-black text. Tertiary = plain text link ("Create Later").
- **Bold moments:** full primary-green screens with the tonal W zigzag pattern behind white text (e.g., employer onboarding) — reserve for one-screen statements.
- **Celebration moments:** the match screen is the canonical confetti use: confetti scattered on off-white, green W mark, "It's a match" headline, two photo cards joined by the double-flame badge.
- **Badges/labels:** small green pills with white text ("Top Match"); white verification rosette on photos.

## Imagery & photography

- Real people, candid energy: mid-laugh, mid-conversation, mid-gesture — the moment a Vibe Video™ captures.
- Natural light, warm tones that harmonize with beige/off-white; subtle green wardrobe/props welcome.
- Diverse ages, roles, and backgrounds — hiring is for everyone.
- ❌ Never: sterile stock handshakes, suits-in-glass-towers, dark moody corporate scenes, fake smiles at whiteboards.

## Image-generation prompt snippets

Use these building blocks with image models (Midjourney/DALL-E/etc.):

**Base style suffix (append to any prompt):**
> …minimal composition, warm off-white background #F7F5F2, vivid green accents #00993A, soft natural light, papery texture, clean geometric layout, generous negative space, no text

**Origami object hero:**
> A single green origami folded-paper letter W standing on a warm off-white paper surface, studio photography, soft shadows, minimal, brand hero image

**Celebration moment:**
> Warm candid photo of a person smiling while recording a video of themselves on a phone, natural window light, subtle green and amber paper confetti falling, off-white interior

**Employer moment:**
> Two people in a bright warm office having a genuine relaxed conversation, natural light, plants, green accents, candid documentary style

Always add: `--no dark corporate office, suits, handshake stock photo, neon, gradients` (or equivalent negative prompt).
