# Worwyn Brand System

**AI-ready brand system for Worwyn** — a personality-first, video-first hiring marketplace.
This repository packages the complete Worwyn brand into files that both **humans** (designers, marketers) and **AI tools** (ChatGPT, Claude) can use to create on-brand content: social media posts, presentations, and campaign material.

> *"You are more than a resume."*

## Quick start

**I want AI to make content for me** → Go to [`04_SETUP/Setup_Instructions.md`](04_SETUP/Setup_Instructions.md). It walks you through setting up a ChatGPT or Claude project with these files in about 5 minutes.

**I'm a designer looking for assets** → Everything is in [`00_ASSETS/`](00_ASSETS/README.md) (logos, patterns, color swatches) and the full brand book is at [`01_BRAND_FOUNDATION/Brandbook.pdf`](01_BRAND_FOUNDATION/Brandbook.pdf).

**I want to make a social post right now** → Follow the matching guide in [`03_CONTENT_SYSTEM/`](03_CONTENT_SYSTEM/) (Instagram / LinkedIn / Presentations) — each defines formats, layouts, and copy formulas, built on the assets in `00_ASSETS/`.

## Repository map

| Folder | What's inside | Use it for |
|---|---|---|
| [`00_ASSETS/`](00_ASSETS/README.md) | Logo files (transparent PNG), brand patterns, color swatches | Dropping real brand assets into any design tool |
| [`01_BRAND_FOUNDATION/`](01_BRAND_FOUNDATION/) | The official brand book (single PDF + individual pages), `Colors.md`, `Typography.md`, `Logo.md` | The source of truth for how the brand looks |
| [`02_AI_GUIDELINES/`](02_AI_GUIDELINES/) | `AI_Brand_Instructions.md`, `Visual_Language.md`, `Tone_of_Voice.md`, `Do_Dont.md` | Teaching an AI assistant to create on-brand content |
| [`03_CONTENT_SYSTEM/`](03_CONTENT_SYSTEM/) | Instagram, LinkedIn and presentation guides + composition checklist | Producing actual posts and decks |
| [`04_SETUP/`](04_SETUP/) | Step-by-step AI setup instructions + `Master_Prompt.txt` | One-time setup of your AI content assistant |

## The brand in one paragraph

Worwyn exists to **make hiring human again**. Résumés don't show personality — they hide it. Worwyn replaces filters and bullet points with presence, energy, and first impressions through **Vibe Videos™** and **Mutual Rise™** matching. The brand speaks with warmth and confidence, looks like folded green paper (the origami "W"), and celebrates every human connection with a touch of confetti.

**Core facts:** Primary green `#00993A` · Typeface **Instrument Sans** (Semibold 600 headlines / Regular 400 body) · Origami folded-paper "W" mark · Tagline *"You are more than a resume"*

## This is a living system

The brand book itself invites it: *evolve the product and generate more designs from these fundamental components.* This repository is a **snapshot, not a cage** — colors may be adjusted, new assets, templates, or platforms may be added, and rules may be refined as Worwyn grows.

When something changes, follow this order:

1. **Change it here first.** This repo is the single source of truth. Update the relevant file (`Colors.md` for a palette change, `00_ASSETS/` for new assets, a new guide in `03_CONTENT_SYSTEM/` for a new platform…) — ideally via a pull request so there's a record of what changed and why.
2. **Keep files consistent.** A color change touches more than one file: `Colors.md`, the swatch in `00_ASSETS/colors/`, `AI_Brand_Instructions.md` (section 2), `Master_Prompt.txt`, and any affected templates. Search the repo for the old hex code to catch every mention.
3. **Re-sync your AI assistants.** Re-upload the changed files to your ChatGPT/Claude project (delete the old copies first) — AI assistants follow the files they were given, not this repo, so they only "learn" changes you re-upload.
4. **Date it.** Note significant changes in the commit message (e.g., "2027-01: primary green updated to #0FA344 per client request") so anyone can trace the brand's evolution.

Anything not yet covered by these files (a new platform, a new format) isn't forbidden — it's simply undesigned. Design it from the foundations in `01_BRAND_FOUNDATION/` and `02_AI_GUIDELINES/`, then document it here.

---

*Brand guidelines created by Spaceberry Studio. Brand system repository assembled 2026.*
