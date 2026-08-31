# Shanxi Museum - Temporary Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `shanximuseum`
- Namespace Name: `Shanxi Museum`
- Route Path: `/shanximuseum/exhibition/temporary/:type?`
- Route Name: `Temporary Exhibitions`
- Example: `/shanximuseum/exhibition/temporary/now&future`
- URL: `www.shanximuseum.com.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `temporary.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Temporary Exhibition type, supported values: now （正在展出）、future（即将展出）、now&future（正在展出&即将展出）、past（往期展览）。Supports multiple status combinations separated by &, + or , (e.g., now&future). Default: All exhibitions (now, future and past).


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.shanximuseum.com.cn/sx/exhibition/temporary.html`
- `target`: `/exhibition/temporary`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/shanximuseum/exhibition/temporary/now&future",
  "heat": 0,
  "location": "temporary.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Temporary Exhibitions",
  "parameters": {
    "type": "Temporary Exhibition type, supported values: now （正在展出）、future（即将展出）、now&future（正在展出&即将展出）、past（往期展览）。Supports multiple status combinations separated by &, + or , (e.g., now&future). Default: All exhibitions (now, future and past)."
  },
  "path": "/exhibition/temporary/:type?",
  "radar": [
    {
      "source": [
        "www.shanximuseum.com.cn/sx/exhibition/temporary.html"
      ],
      "target": "/exhibition/temporary"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
