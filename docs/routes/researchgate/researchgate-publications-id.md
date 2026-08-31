# ResearchGate - Publications

## Coverage
`index-only`

## Route
- Namespace: `researchgate`
- Namespace Name: `ResearchGate`
- Route Path: `/researchgate/publications/:id`
- Route Name: `Publications`
- Example: `/researchgate/publications/Somsak-Panha`
- URL: `researchgate.net`
- Language: `_None_`
- Categories: `study`
- Maintainers: `nczitzk`
- Source Location: `publications.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Username, can be found in URL


## Features
- `requirePuppeteer`: true
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `researchgate.net/profile/:username`
- `target`: `/publications/:username`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/researchgate/publications/Somsak-Panha",
  "features": {
    "antiCrawler": true,
    "requirePuppeteer": true
  },
  "heat": 0,
  "location": "publications.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Publications",
  "parameters": {
    "id": "Username, can be found in URL"
  },
  "path": "/publications/:id",
  "radar": [
    {
      "source": [
        "researchgate.net/profile/:username"
      ],
      "target": "/publications/:username"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
