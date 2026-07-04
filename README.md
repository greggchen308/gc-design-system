# GC Artifacts — Workshop Design System

Component library for gcartifacts.com ("Workshop" visual direction, July 2026).
7 self-contained preview cards, each with a `@dsCard` group marker on line 1:

- `foundations/colors.html` — palette, light + dark themes, usage rules
- `foundations/typography.html` — Sora display / DM Sans body / Gochi Hand annotations
- `foundations/voice.html` — brand voice rules (always / never)
- `components/buttons.html` — primary (yellow fill) / secondary (outline)
- `components/sticker-card.html` — tilted default + straight Training variant
- `components/annotations.html` — squiggle underline + margin notes
- `components/portrait.html` — circular portrait treatment

Source of truth: `Fable_Astro_Refresh_July_2026.md` Part 2 in the gregg-portfolio project.

## Sync instructions (paste this into a claude.ai/code web session opened on this repo)

> Sync this design system to Claude Design: create a design-system project named
> "GC Artifacts — Workshop" (or use it if it already exists), then push all 7 HTML
> files in foundations/ and components/ preserving their paths. Each file already
> carries its @dsCard group marker on line 1 — do not modify file contents.
> Follow the DesignSync order: list → finalize_plan → write_files.
