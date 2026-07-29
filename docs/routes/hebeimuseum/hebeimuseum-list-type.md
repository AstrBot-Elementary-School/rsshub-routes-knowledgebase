# Hebei Museum - Temporary Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `hebeimuseum`
- Namespace Name: `Hebei Museum`
- Route Path: `/hebeimuseum/list/:type?`
- Route Name: `Temporary Exhibitions`
- Example: `/hebeimuseum/list/special`
- URL: `www.hebeimuseum.org.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `list.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: special（临时展览详情）. Default: All.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.hebeimuseum.org.cn/list-26-1.html`
- `target`: `/list`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/hebeimuseum/list/special",
  "heat": 0,
  "location": "list.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Temporary Exhibitions",
  "parameters": {
    "type": "Exhibition type, supported values: special（临时展览详情）. Default: All."
  },
  "path": "/list/:type?",
  "radar": [
    {
      "source": [
        "www.hebeimuseum.org.cn/list-26-1.html"
      ],
      "target": "/list"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
