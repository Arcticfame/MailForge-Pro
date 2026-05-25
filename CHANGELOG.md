# Changelog

## v5.0.0 — 2026-05-26

### New
- **Tool 10: Email Verifier** — offline heuristic checker: syntax, disposable-domain (200+ list), role-account, free vs business, score/100; CSV export
- **Dark / Light / System theme** — CSS variable theming, persisted via localStorage
- **Command Palette** (Ctrl+K / /) — fuzzy search, arrow-key nav, Enter to open tool
- **PWA manifest** — installable as desktop/mobile app, offline capable

### Upgraded — Tool 3 (Variation Generator)
- Real-time spam-trigger word checker on subject line (60+ trigger words)
- Spam score 0–100 with colour indicator

### Upgraded — Tool 5 (Deduplicator)
- Gmail normalisation (strips dots & +tags, maps googlemail.com → gmail.com)
- Cross-list compare panel: A∩B, A−B, B−A, A∪B with stats

### Upgraded — Tool 6 (Bulk Tools)
- Find & Replace with full regex support and flags (case-insensitive toggle)
- Sort panel: 6 modes (alpha asc/desc, length asc/desc, by domain, random)
- Case transform: lowercase, UPPERCASE, Title Case, trim whitespace

### Upgraded — Tool 7 (Randomizer)
- Seeded PRNG via Mulberry32 algorithm (same seed → same output, reproducible)
- Sample-N mode: pick N random items without replacement

### Upgraded — Tool 9 (Column Converter)
- Output format selector: Delimited (default), JSON Array, JSON Lines, SQL INSERT, Markdown Table, HTML Table
- Table & column name inputs for SQL/MD/HTML modes

### Removed
- Google Analytics (gtag) — restores 100% local, zero-tracking promise

### Polish
- Version bump v4.0 → v5.0 everywhere
- Sidebar: "10 tools available" count
- Footer: updated copy

## v4.0.0

- Professional UI redesign: Inter font, SVG sidebar icons
- Complete CSS design system overhaul with shadow hierarchy

## v3.0.0 — (baseline)

- 9 tools: LeadSeed, Splitter, VariGen, Extractor, Dedup, Bulk, Randomizer, Img Renamer, Col Converter
- Sidebar search, keyboard shortcuts 1–9, back-to-top button
