# Thinking Machines Lab - News

## Coverage
`index-only`

## Route
- Namespace: `thinkingmachines`
- Namespace Name: `Thinking Machines Lab`
- Route Path: `/thinkingmachines/news`
- Route Name: `News`
- Example: `/thinkingmachines/news`
- URL: `thinkingmachines.ai/news`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `w3nhao`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false

## Radar
### Rule 1
- `source`:
  - `thinkingmachines.ai/news`
  - `thinkingmachines.ai/news/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/thinkingmachines/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false
  },
  "heat": 2,
  "location": "news.ts",
  "maintainers": [
    "w3nhao"
  ],
  "name": "News",
  "path": "/news",
  "radar": [
    {
      "source": [
        "thinkingmachines.ai/news",
        "thinkingmachines.ai/news/"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Thinking Machines Lab - News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "268937864442547200",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://thinkingmachines.ai/news/",
      "title": "Thinking Machines Lab - News",
      "type": "feed",
      "url": "rsshub://thinkingmachines/news"
    }
  ],
  "url": "thinkingmachines.ai/news"
}
```
