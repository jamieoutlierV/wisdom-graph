# The Well — Wisdom Graph

A curated graph of the world's mythic and archetypal wisdom. The canonical corpus for [The Well](https://www.notmachine.art/thewell), a living experiential artwork by N0tMach1ne Studio.

## What This Is

This repository is the **source of truth** for The Well's Wisdom Graph — the curated corpus of stories, archetypes, traditions, places, calendar events, and cross-traditional resonances that The Well draws from.

Every entry is a YAML file with rich metadata: cultural attribution, archetypal tagging, emotional registers, place-linking, calendar associations, sensitivity notes, and permission levels.

## Structure

```
wisdom-graph/
├── .schema/            # Schema definitions for each entity type
├── stories/            # Mythic material, organised by tradition
│   ├── greek/
│   ├── norse/
│   ├── celtic/
│   ├── hindu/
│   ├── buddhist/
│   ├── jewish/
│   ├── taoist/
│   ├── yoruba/
│   └── sumerian/
├── archetypes/         # Archetypal patterns (The Descent, The Trickster, etc.)
├── traditions/         # Tradition metadata and calendar systems
├── places/             # Place entities with ancient names and spatial ontologies
├── resonances/         # Cross-traditional pairings — resonance AND difference
└── calendar-events/    # Mythic calendar dates and seasonal associations
```

## Principles

1. **Always name the source.** Every story is attributed to its tradition and culture. No orphaned wisdom.
2. **Resonance AND difference.** Cross-traditional pairings always name both what's shared and what crucially diverges.
3. **Concentric rings of permission.** Archaeological → Historical → Publicly Shared → Restricted/Sovereign. We do not include material from Ring 4 (restricted/sovereign) without explicit community partnership.
4. **Place is a dimension.** Stories belong to landscapes. The graph encodes where wisdom comes from.
5. **The Keepers tend, the Council reviews.** Autonomous agents propose entries; the advisory council validates.

## Contributing

This corpus is curated, not crowdsourced. Contributions are welcome through Pull Requests, which are reviewed by the advisory council. See CONTRIBUTING.md (forthcoming) for guidelines.

## Seed Status (March 2026)

- **12 stories** across 7 traditions (Greek, Norse, Sumerian, Jewish, Yoruba, Taoist, Celtic, Buddhist, Hindu)
- **3 archetypes** (The Descent, The Trickster, The Return)
- **2 resonances** (Persephone-Inanna, Odysseus-Oisín)
- **1 place** (Tamesis / London)
- All entries in `draft` status pending advisory council review

## License

Stories are drawn from public domain sources. The graph structure, tagging, resonances, and curatorial work are © N0tMach1ne Studio. API terms forthcoming.

---

*A N0tMach1ne Studio Art Project — [notmachine.art](https://www.notmachine.art)*
