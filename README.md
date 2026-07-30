# RSSHub Routes Knowledgebase

This branch is generated automatically from RSSHub official route metadata.

## Summary
- Generated At: `2026-07-30T06:00:36+00:00`
- Source Repo: `https://github.com/DIYgod/RSSHub`
- Source Revision: `6f50d57298dbc1a9cffc65af1ab123facb65a4b2`
- Namespaces: `1686`
- Route Documents: `3318`
- Categories: `25`

## Files
- `metadata.json`: machine-readable manifest for incremental sync.
- `index/namespaces.md`: top-level namespace directory.
- `index/<namespace>.md`: per-namespace route directory.
- `docs/routes/<namespace>/*.md`: per-route markdown documents.

## Sync
- Use `metadata.json` as the canonical file manifest for incremental updates.
- Compare `files[].path` and `files[].sha256` to determine additions, updates, and deletions.

## Suggested Lookup Flow
1. Read `index/namespaces.md` to identify the target namespace.
2. Read `index/<namespace>.md` to choose the best matching route file.
3. Read the selected `docs/routes/...` file for the full route knowledge.

