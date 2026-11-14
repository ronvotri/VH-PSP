# The 3rd Birthday — QA Checkpoint 18

- Source rows: **5,599** (original ID and English columns preserved)
- Total translated IDs: **2549** (45.5%)
- Newly translated in batch 18: **320**, covering IDs 5331–5653 (sparse original IDs retained)
- New translations: **320/320** pass exact placeholder and literal `\\n` count comparison
- Fixed 12 draft newline discrepancies before checkpoint merge (5485, 5496, 5501, 5502, 5511, 5521, 5549, 5550, 5625, 5626, 5635, 5648)
- No duplicate or pre-existing IDs overwritten
- New strings do not exceed the preliminary length flag `Vietnamese characters > 1.4 × source character limit + 15`; this is **not** PSP pixel-width QA
- Existing **40** newline/layout warnings from checkpoints 13–17 remain open for editorial review
- No in-game PSP/PPSSPP font and line wrapping validation completed

## Previously unresolved warnings

# Checkpoint 17 QA

- New: 38 entries; token and literal newline matching 38/38.
- Total translated: 2229 of 5599.
- Prior 40 newline layout warnings from checkpoint 16 remain open.
- Not in-game tested.
