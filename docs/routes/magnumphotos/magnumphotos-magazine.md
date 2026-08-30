# Magnum Photos - Magazine

## Coverage
`index-only`

## Route
- Namespace: `magnumphotos`
- Namespace Name: `Magnum Photos`
- Route Path: `/magnumphotos/magazine`
- Route Name: `Magazine`
- Example: `/magnumphotos/magazine`
- URL: `magnumphotos.com/`
- Language: `_None_`
- Categories: `picture, popular`
- Maintainers: `IvanWng97`
- Source Location: `magazine.ts`
- Source Module: `_None_`

## Description
_None_

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
  - `magnumphotos.com/`

## Raw JSON
```json
{
  "categories": [
    "picture",
    "popular"
  ],
  "example": "/magnumphotos/magazine",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 43490,
  "location": "magazine.ts",
  "maintainers": [
    "IvanWng97"
  ],
  "name": "Magazine",
  "parameters": {},
  "path": "/magazine",
  "radar": [
    {
      "source": [
        "magnumphotos.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Magnum is a community of thought, a shared human quality, a curiosity about what is going on in the world, a respect for what is going on and a desire to transcribe it visually - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41700553415750656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.magnumphotos.com/",
      "title": "Magnum Photos",
      "type": "feed",
      "url": "rsshub://magnumphotos/magazine"
    }
  ],
  "url": "magnumphotos.com/",
  "view": 2
}
```
