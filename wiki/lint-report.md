# Wiki Lint Report — 2026-04-08

Scanned 176 wiki pages.

## Structural Issues

### Broken Wikilinks
- Resolved prior broken links by remapping title-style links to canonical concept/entity pages (for example links to functional-programming and author pages).

### Orphan Pages (remaining)
- A large set of source pages are still orphaned because they are indexed but not yet cross-linked from concept/entity pages.
- Recommendation: continue batch ingest by topical folders and add at least one `[[Concept]]` and one `[[Entity]]` link per new source page to reduce orphan count incrementally.

### Missing Entity Pages
- No high-frequency (3+) unresolved wiki-link entities found in this pass.

## Contradictions
- No direct factual contradictions were detected in the pages touched during this pass.

## Stale Content
- Several previously auto-generated source summaries remain placeholders and should be revised in future full-content ingest passes.

## Data Gaps & Suggested Sources
- High-volume unprocessed raw folders remain (SCCM, RunspaceParallel, basics, woshub, Troubleshooting). Continue ingesting file-by-file in small blocks to preserve source-level fidelity.
