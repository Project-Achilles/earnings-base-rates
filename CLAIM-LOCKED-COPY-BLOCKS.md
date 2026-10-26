# Claim-Locked Copy Blocks — Library v1 (DRAFT, for ISA's one-time clearance)

Purpose (the E2E relief valve, census task 1219873993148389): sentences cleared ONCE by ISA and then reused VERBATIM — in outreach, posts, dataset cards, journalist replies, and page furniture — so verification stops being a per-use toll. Rules: a block is used byte-identical or not at all · any edit returns the block to ISA · figures inside blocks are ISA-01 locked only, with AS_OF on the block's face · no block may be combined with an uncleared figure.

## Block A — Attribution (rides any use of the data)

> Earnings-move base rates by Read Achilles, data as of <AS_OF>.

(AS_OF is the only variable field; it takes the figure set's own date, never today's.)

## Block B — What a base rate is (definition, 40 words)

> An earnings base rate is the measured history of how a stock actually moved after its past earnings reports: how many prints were priced, how often the move exceeded a given size, and the median move. It is a count, not a forecast.

## Block C — The figure sentence (template; locked order: hit rate · median · N · AS_OF)

> Across <N> priced earnings prints, <SYMBOL> moved more than ±5% <HIT_RATE>% of the time, with a median absolute move of <MEDIAN>% (data as of <AS_OF>).

Filled only from a locked ISA-01 row (or a certified print update under the same lock). The hit-rate definition ("share of priced prints moving more than ±5%") is inside the sentence by construction.

## Block D — Pooled context (scale only, never a symbol claim)

> For scale: across 24,203 priced earnings prints in the atlas, 17.12% moved more than ±5% (data as of 2026-10-09).

## Block E — Non-affiliation / independence

> Read Achilles is an independent research and education publisher. It is not affiliated with, endorsed by, or acting on behalf of any company, exchange, or institution named in its data, and nothing it publishes is investment advice.

## Block F — Method in one breath

> The figures are counted from the prints themselves: every earnings reaction in the set was observed, classified by size, and counted. No options-implied estimates, no analyst consensus, no means — hit rates and medians, each with its print count beside it.

## Block G — Dataset citation (for the open-data surfaces)

> Dataset: "Earnings-Move Base Rates — ISA-01 Extract," Read Achilles, data as of 2026-10-23. https://readachilles.com/trends/

## Not blocks (standing exclusions)

Titles and headlines never carry figures (ISA's YouTube/audio ruling, generalized). No block exists for guidance grades (nothing below n_testable ≥ 10 is ever stated). No block may be localized, translated, or "improved" without returning to ISA.

— Drafted by Achilles Social 2026-10-26 under the founder's implementation order. **Status: CLEARED by ISA 2026-10-26** (read: ~/workspace/isa-packages/ISA-OPEN-DATA-FILING-1-AND-COPY-BLOCKS-READ-2026-10-26.md), with three conditions, which bind every use:
1. **Block D is a FIXED sentence, not a template** — any refresh of its pooled figures returns it to ISA's bench before use.
2. **Block C never fills from a small_n row** — the block has no flag field, and the flag must travel; small_n symbols are simply never quoted through Block C.
3. **Block G is pinned to the 2026-10-23 extract** — a re-issued extract returns Block G to ISA with its new pin.
This file is the library of record; every reuse cites its block letter.
