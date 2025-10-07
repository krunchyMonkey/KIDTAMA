# KIDTAMA — Project Instructions

**Canonical source of truth:** https://github.com/krunchyMonkey/KIDTAMA/blob/main/README.md  
**Repo home:** https://github.com/krunchyMonkey/KIDTAMA

## Folder rules
- `assets/characters/` — character refs (PNG preferred, lowercase-hyphen names).
- `assets/covers/` — cover/poster art; include `_v1`, `_final` suffixes.
- `assets/scenes/` — scene illustrations/b-roll.
- `scripts/<arc_name>/` — episode markdown files.
- `docs/` — meta docs, templates, prompt guides.

## Naming & conventions
- Files: `emi-wooden-sword.png`, `episode1-the-day-breakfast-fought-back.md`
- Branches: `feature/<topic>` or `art/<scene-name>`
- Commits: `feat(script): ep2 syrup rebellion`, `art(cover): add ezra`

## Content rules (short)
- Tone: “Gintama energy + heart.” Keep it family-friendly.
- Character traits must match the Story Bible (README).
- Writing: 1–2k words/episode, third-person, snappy dialogue.
- Visuals: Anime aesthetic; use character refs from `assets/characters/`.

## PR checklist
- [ ] Links to character refs in description
- [ ] Updated `README.md` tables or `docs/continuity_tracker.md` if canon changed
- [ ] New images in correct folders with alt text in scripts
- [ ] Build passes (PDF export action optional)

## File templates
- Use: `docs/episode_template.md`, `docs/arc_template.md`, `docs/character_template.md`
