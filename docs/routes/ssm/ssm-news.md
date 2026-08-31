# 澳门卫生局 - 最新消息

## Coverage
`index-only`

## Route
- Namespace: `ssm`
- Namespace Name: `澳门卫生局`
- Route Path: `/ssm/news`
- Route Name: `最新消息`
- Example: `/ssm/news`
- URL: `www.ssm.gov.mo/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `news.tsx`
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
  - `www.ssm.gov.mo/`
  - `www.ssm.gov.mo/portal`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/ssm/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "最新消息",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.ssm.gov.mo/",
        "www.ssm.gov.mo/portal"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.ssm.gov.mo/"
}
```
