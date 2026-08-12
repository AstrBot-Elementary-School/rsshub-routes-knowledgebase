# NL Times - News

## Coverage
`index-only`

## Route
- Namespace: `nltimes`
- Namespace Name: `NL Times`
- Route Path: `/nltimes/news/:category?`
- Route Name: `News`
- Example: `/nltimes/news/top-stories`
- URL: `nltimes.nl`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Hivol`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| Top Stories (default) | Health | Crime | Politics | Business | Tech | Culture | Sports | Weird | 1-1-2 |
| --------------------- | ------ | ----- | -------- | -------- | ---- | ------- | ------ | ----- | ----- |
| top-stories           | health | crime | politics | business | tech | culture | sports | weird | 1-1-2 |

## Parameters
- `category`: category


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
  - `nltimes.nl/categories/:category`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Top Stories (default) | Health | Crime | Politics | Business | Tech | Culture | Sports | Weird | 1-1-2 |\n| --------------------- | ------ | ----- | -------- | -------- | ---- | ------- | ------ | ----- | ----- |\n| top-stories           | health | crime | politics | business | tech | culture | sports | weird | 1-1-2 |",
  "example": "/nltimes/news/top-stories",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "news.ts",
  "maintainers": [
    "Hivol"
  ],
  "name": "News",
  "parameters": {
    "category": "category"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "nltimes.nl/categories/:category"
      ],
      "target": "/news/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "NL Times -- Top Stories - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59769816692412416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nltimes.nl/top-stories",
      "title": "NL Times -- Top Stories",
      "type": "feed",
      "url": "rsshub://nltimes/news/top-stories"
    },
    {
      "description": "NL Times -- Politics - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "180670433614968832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nltimes.nl/categories/politics",
      "title": "NL Times -- Politics",
      "type": "feed",
      "url": "rsshub://nltimes/news/politics"
    }
  ]
}
```
