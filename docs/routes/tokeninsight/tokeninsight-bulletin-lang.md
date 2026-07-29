# TokenInsight - Latest

## Coverage
`index-only`

## Route
- Namespace: `tokeninsight`
- Namespace Name: `TokenInsight`
- Route Path: `/tokeninsight/bulletin/:lang?`
- Route Name: `Latest`
- Example: `/tokeninsight/bulletin/en`
- URL: `tokeninsight.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `fuergaosi233`
- Source Location: `bulletin.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: Language, see below, Chinese by default


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
  - `tokeninsight.com/:lang/latest`
- `target`: `/bulletin/:lang`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/tokeninsight/bulletin/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "bulletin.ts",
  "maintainers": [
    "fuergaosi233"
  ],
  "name": "Latest",
  "parameters": {
    "lang": "Language, see below, Chinese by default"
  },
  "path": "/bulletin/:lang?",
  "radar": [
    {
      "source": [
        "tokeninsight.com/:lang/latest"
      ],
      "target": "/bulletin/:lang"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
