# The receipts: verified AI failures in production

A library of documented AI failures in production, each verified against a
primary source: a regulator's order, a court record, the company's own
statement, or a named newsroom. One record per incident with the organizations
involved, when it happened, the failure class, who discovered it, whether the
organization running the AI caught it, the control that was missing, and the
sources. A second table, `refuted`, holds AI failure stories that were checked
at the source and not found there, with what was searched and what is real.

**Version 2026.09.01. 26 incidents, 4 refuted claims.**

The canonical, always-current copy is https://walkeraisystems.com/receipts.
Every incident has its own page at `/receipts/<slug>`. This repository mirrors
the machine-readable exports and tags each version so a citation resolves to
the exact state it was drawn from.

## Files

- `receipts.json`: the full dataset with field definitions, method notes, the
  six control groups, the incident records and the refuted claims.
- `receipts.csv`: the incident records only, one row each.

## Cite as

Walker AI Systems LLC (2026). The receipts: verified AI failures in production, version 2026.09.01. https://walkeraisystems.com/receipts

BibTeX is inside `receipts.json` under `bibtex`.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Use it, build on
it, and credit Walker AI Systems LLC with a link to the canonical URL.

## How entries get in, and how they get corrected

Nothing is published from an aggregator. Each incident is read at its primary
source before publication; claims that cannot be found go to the refuted list
rather than being dropped, so the library can answer a false story rather than
only lack it. Corrections are made on the record itself with the date of the
first reading and the date of the fix. The method, in full:
https://walkeraisystems.com/receipts#method
