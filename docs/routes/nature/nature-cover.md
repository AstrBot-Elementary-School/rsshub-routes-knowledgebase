# Nature Journal - Cover Story

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/nature/cover`
- Route Name: `Cover Story`
- Example: `/nature/cover`
- URL: `nature.com/`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, pseudoyu`
- Source Location: `cover.ts`
- Source Module: `_None_`

## Description
Subscribe to the cover images of the Nature journals, and get the latest publication updates in time.

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
  - `nature.com/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "Subscribe to the cover images of the Nature journals, and get the latest publication updates in time.",
  "example": "/nature/cover",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 30,
  "location": "cover.ts",
  "maintainers": [
    "y9c",
    "pseudoyu"
  ],
  "name": "Cover Story",
  "parameters": {},
  "path": "/cover",
  "radar": [
    {
      "source": [
        "nature.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Find out the cover story of some Nature journals. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78348485116004352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/",
      "title": "Nature Covers Story",
      "type": "feed",
      "url": "rsshub://nature/cover"
    }
  ],
  "url": "nature.com/"
}
```
