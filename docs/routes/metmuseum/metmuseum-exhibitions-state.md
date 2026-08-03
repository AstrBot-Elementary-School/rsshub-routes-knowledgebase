# The Metropolitan Museum of Art - Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `metmuseum`
- Namespace Name: `The Metropolitan Museum of Art`
- Route Path: `/metmuseum/exhibitions/:state?`
- Route Name: `Exhibitions`
- Example: `/metmuseum/exhibitions`
- URL: `www.metmuseum.org`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `chazeon`
- Source Location: `exhibitions.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `state`: 展览进行的状态：`current` 对应展览当前正在进行，`past` 对应过去的展览，`upcoming` 对应即将举办的展览，默认为 `current`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/metmuseum/exhibitions",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "exhibitions.ts",
  "maintainers": [
    "chazeon"
  ],
  "name": "Exhibitions",
  "parameters": {
    "state": "展览进行的状态：`current` 对应展览当前正在进行，`past` 对应过去的展览，`upcoming` 对应即将举办的展览，默认为 `current`"
  },
  "path": "/exhibitions/:state?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
