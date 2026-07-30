# 财经网 - 滚动新闻

## Coverage
`index-only`

## Route
- Namespace: `caijing`
- Namespace Name: `财经网`
- Route Path: `/caijing/roll`
- Route Name: `滚动新闻`
- Example: `/caijing/roll`
- URL: `roll.caijing.com.cn/index1.html`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `roll.ts`
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
  - `roll.caijing.com.cn/index1.html`
  - `roll.caijing.com.cn/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/caijing/roll",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 226,
  "location": "roll.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "滚动新闻",
  "parameters": {},
  "path": "/roll",
  "radar": [
    {
      "source": [
        "roll.caijing.com.cn/index1.html",
        "roll.caijing.com.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "滚动新闻-财经网 - Powered by RSSHub",
      "errorAt": "2025-05-12T11:21:50.287Z",
      "errorMessage": "[GET] \"https://roll.caijing.com.cn/ajax_lists.php?modelid=0&time=0.4446400573443805\": 403 Forbidden\n",
      "id": "59951906827705344",
      "image": "https://www.caijing.com.cn/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "滚动新闻-财经网",
      "type": "feed",
      "url": "rsshub://caijing/roll"
    }
  ],
  "url": "roll.caijing.com.cn/index1.html"
}
```
