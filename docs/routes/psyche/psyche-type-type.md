# Psyche - Types

## Coverage
`index-only`

## Route
- Namespace: `psyche`
- Namespace Name: `Psyche`
- Route Path: `/psyche/type/:type`
- Route Name: `Types`
- Example: `/psyche/type/ideas`
- URL: `psyche.co`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `type.ts`
- Source Module: `_None_`

## Description
Supported types: Ideas, Guides, and Films.

## Parameters
- `type`: Type


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
  - `psyche.co/ideas`
- `target`: `/type/ideas`
### Rule 2
- `source`:
  - `psyche.co/guides`
- `target`: `/type/guides`
### Rule 3
- `source`:
  - `psyche.co/films`
- `target`: `/type/films`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Supported types: Ideas, Guides, and Films.",
  "example": "/psyche/type/ideas",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "type.ts",
  "maintainers": [
    "emdoe"
  ],
  "name": "Types",
  "parameters": {
    "type": "Type"
  },
  "path": "/type/:type",
  "radar": [
    {
      "source": [
        "psyche.co/ideas"
      ],
      "target": "/type/ideas"
    },
    {
      "source": [
        "psyche.co/guides"
      ],
      "target": "/type/guides"
    },
    {
      "source": [
        "psyche.co/films"
      ],
      "target": "/type/films"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
