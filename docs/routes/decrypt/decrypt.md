# Decrypt - News

## Coverage
`index-only`

## Route
- Namespace: `decrypt`
- Namespace Name: `Decrypt`
- Route Path: `/decrypt/`
- Route Name: `News`
- Example: `/decrypt`
- URL: `decrypt.co`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Get latest news from Decrypt.

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `decrypt.co/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Get latest news from Decrypt.",
  "example": "/decrypt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "News",
  "parameters": {},
  "path": "/",
  "radar": [
    {
      "source": [
        "decrypt.co/"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
