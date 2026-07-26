# 后续 - 跟踪

## Coverage
`index-only`

## Route
- Namespace: `houxu`
- Namespace Name: `后续`
- Route Path: `/houxu/memory`
- Route Name: `跟踪`
- Example: `/houxu/memory`
- URL: `houxu.app/memory`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `memory.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `houxu.app/memory`
  - `houxu.app/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/houxu/memory",
  "heat": 14,
  "location": "memory.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "跟踪",
  "path": "/memory",
  "radar": [
    {
      "source": [
        "houxu.app/memory",
        "houxu.app/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "后续 - 跟踪 - Powered by RSSHub",
      "errorAt": "2025-12-22T08:11:45.061Z",
      "errorMessage": "[GET] \"https://houxu.app/api/1/lives/updated?limit=50\": <no response> fetch failed (redirect count exceeded)\n",
      "id": "55873602868576335",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://houxu.app/memory",
      "title": "后续 - 跟踪",
      "type": "feed",
      "url": "rsshub://houxu/memory"
    }
  ],
  "url": "houxu.app/memory"
}
```
