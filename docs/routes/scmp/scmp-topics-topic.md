# Corona Virus Disease 2019 - Topics

## Coverage
`index-only`

## Route
- Namespace: `scmp`
- Namespace Name: `Corona Virus Disease 2019`
- Route Path: `/scmp/topics/:topic`
- Route Name: `Topics`
- Example: `/scmp/topics/coronavirus-pandemic-all-stories`
- URL: `scmp.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: Topic, can be found in URL


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
  - `scmp.com/topics/:topic`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/scmp/topics/coronavirus-pandemic-all-stories",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "topic.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Topics",
  "parameters": {
    "topic": "Topic, can be found in URL"
  },
  "path": "/topics/:topic",
  "radar": [
    {
      "source": [
        "scmp.com/topics/:topic"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
