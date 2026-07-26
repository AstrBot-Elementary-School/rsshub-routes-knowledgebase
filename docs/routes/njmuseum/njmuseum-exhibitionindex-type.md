# Nanjing Museum - Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `njmuseum`
- Namespace Name: `Nanjing Museum`
- Route Path: `/njmuseum/exhibitionIndex/:type?`
- Route Name: `Exhibitions`
- Example: `/njmuseum/exhibitionIndex/review`
- URL: `www.njmuseum.com/zh`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `exhibitionindex.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: review (展览回顾) | abroad (赴外展览) | virtual (虚拟展厅) | forecast (展览预告). Default: Current Exhibitions (正在展出).


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.njmuseum.com/zh/exhibitionIndex`
- `target`: `/exhibitionIndex`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/njmuseum/exhibitionIndex/review",
  "heat": 0,
  "location": "exhibitionindex.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Exhibitions",
  "parameters": {
    "type": "Exhibition type, supported values: review (展览回顾) | abroad (赴外展览) | virtual (虚拟展厅) | forecast (展览预告). Default: Current Exhibitions (正在展出)."
  },
  "path": "/exhibitionIndex/:type?",
  "radar": [
    {
      "source": [
        "www.njmuseum.com/zh/exhibitionIndex"
      ],
      "target": "/exhibitionIndex"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
