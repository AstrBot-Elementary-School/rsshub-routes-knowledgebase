# RSSHub Routes Knowledgebase

This branch is generated automatically from RSSHub official route metadata.

## Summary
- Generated At: `2026-09-03T08:06:33+00:00`
- Source Repo: `https://github.com/DIYgod/RSSHub`
- Source Revision: `cca82db4d10dc03b4caf2f100dea919223c9f617`
- Namespaces: `1980`
- Route Documents: `3805`
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

