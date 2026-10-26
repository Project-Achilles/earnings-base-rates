# Earnings-Move Base Rates — ISA-01 Extract (as of 2026-10-23)

**What this is.** For 524 US-listed companies, how much the stock actually moved after earnings — counted from the prints themselves, not estimated from options or opinion. For each company: how many earnings prints were priced, the share of those prints that moved more than ±2 / ±3 / ±5 / ±8 / ±10 percent, the median absolute move, and the largest up and down moves on record.

**Data as of 2026-10-23.** Print history per company runs from its first print date to its last print date as carried in the source (latest last print: 2026-10-16).

**Source.** ISA-01 Earnings-Move Atlas (Read Achilles research desk), certified extract: `data/isa01-base-rate-extract-asof-2026-10-23.csv` (md5 `0088e356d00ea096cb8a1ac68736222b`), filtered from the atlas of record (md5 `b987bc8106c49c127795c1c148c4cb75`) to one row per symbol, all eras. Derived statistics only — no raw market data is redistributed.

**Definitions (they travel with the figures).**
- A *priced print* is an earnings release with an observable market reaction in the atlas.
- *Hit rate at ±X%* = the share of a company's priced prints whose absolute move exceeded X%.
- *Median absolute move* is always read with its N (the company's priced-print count, `n_priced`).
- `small_n = TRUE` flags 8 of the 524 companies whose print counts are small; their rows carry the flag unaltered, and the flag must travel with any use of those rows.

**How to cite.** "Earnings-move base rates by Read Achilles, data as of 2026-10-23" — with a link to https://readachilles.com/trends/ . The per-symbol pages on readachilles.com carry the same figures in context.

**Licence.** Attribution-required: you may use these derived statistics in analysis, products, and publications with the citation above. The figures may not be re-presented as your own measurement.

**Verification.** Every figure in this dataset was verified against the certified ISA-01 source before publication by the Read Achilles verification bench (ISA). Nothing in this dataset is computed at publication time.
