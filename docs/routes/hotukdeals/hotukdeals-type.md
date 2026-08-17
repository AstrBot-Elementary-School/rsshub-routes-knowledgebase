# hotukdeals - thread

## Coverage
`index-only`

## Route
- Namespace: `hotukdeals`
- Namespace Name: `hotukdeals`
- Route Path: `/hotukdeals/:type`
- Route Name: `thread`
- Example: `/hotukdeals/hot`
- URL: `www.hotukdeals.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `DIYgod`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: should be one of highlights, hot, new, discussed


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
    "shopping"
  ],
  "example": "/hotukdeals/hot",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "thread",
  "parameters": {
    "type": "should be one of highlights, hot, new, discussed"
  },
  "path": "/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected { '$': { isPermaLink: 'false' } } to deeply equal Any<String>\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:84:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
