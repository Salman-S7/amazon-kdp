# A2 - Women of the Bible Large Print Word Search

A2 is the second title in the Christian/Bible large-print puzzle pilot.

## Product role

**Targeted audience extension:** a focused companion to A1 that explores the women of Scripture through a calm, readable, curated puzzle experience.

## Core product promise

**A relaxing large-print journey through the courage, faith, wisdom, perseverance, and service of women throughout the Bible.**

The book should feel related to A1 without feeling like a reskin.

## Current retail build

- Trim: 8.5 x 11 in
- Interior: black-and-white, no bleed
- Page count: 104
- Puzzle count: 60
- Grid: 16 x 16
- Main words per puzzle: 15
- Main answers: 900 total
- Difficulty mix: 42 Relaxed / 12 Medium / 6 Challenge
- Challenge positions: 10, 20, 30, 40, 50, 60
- Bonus challenge: one additional named bonus word on each Challenge puzzle
- Solutions: 30 pages, two enlarged solutions per page
- Five section-opening pages
- Three-page large-type puzzle index
- Bible-focus reference + original context on every puzzle
- Completion tracking on every puzzle
- Two closing/reflection pages
- Embedded fonts only

## Five equal sections

Each section contains exactly 12 puzzles:

1. Beginnings & Family - puzzles 1-12
2. Courage in the Promised Land & Kingdom - puzzles 13-24
3. Wisdom, Prophecy & Queens - puzzles 25-36
4. Women in the Life & Ministry of Jesus - puzzles 37-48
5. Witness, Service & the Early Church - puzzles 49-60

See `V1_60_PUZZLE_ARCHITECTURE.md` for the complete theme sequence and `PRODUCTION_V1.md` for the generated-build QA record.

## Differentiation from A1

- Target at least 80% unique theme/vocabulary combinations.
- Only use a repeated A1 figure when A2 provides a clearly different editorial lens.
- Favor specific women, relationships, decisions, places, roles, and actions over generic faith filler.
- Include both famous and lesser-known women so the book rewards discovery.
- Do not reduce biblical women to generic motivational traits; retain concrete scriptural context.
- Use original summaries and references rather than reproducing copyrighted modern Bible-translation text.

## Production method

1. Curated 60-theme architecture.
2. Reference + original context + 15-word vocabulary data for every puzzle.
3. Spelling, duplicate, character, and grid-length validation.
4. Deterministic 16 x 16 grid generation.
5. Exact answer coordinates stored for every intended answer.
6. Physical-path validation verifies each intended answer occurs exactly once.
7. Duplicate grids are rejected.
8. Solutions are rendered from stored coordinates.
9. Layout-risk checks verify long titles, contexts, and word lists fit.
10. All 104 pages are rendered and visually sampled.
11. PDF preflight verifies page count, openability, size, and embedded fonts.

## Current status

- [x] Product role locked
- [x] 60-puzzle section architecture
- [x] References/context/vocabulary dataset
- [x] Puzzle generation
- [x] Automated answer-path validation
- [x] 104-page interior rendering
- [x] PDF preflight and visual render QA
- [ ] Final human biblical/editorial review
- [ ] Cover
- [ ] Metadata / keywords / categories
- [ ] KDP Previewer
- [ ] Physical proof and 55+ readability test
