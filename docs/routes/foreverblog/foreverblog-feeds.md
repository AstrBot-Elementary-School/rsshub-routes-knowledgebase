# 十年之约 - 专题展示 - 文章

## Coverage
`index-only`

## Route
- Namespace: `foreverblog`
- Namespace Name: `十年之约`
- Route Path: `/foreverblog/feeds`
- Route Name: `专题展示 - 文章`
- Example: `/foreverblog/feeds`
- URL: `www.foreverblog.cn/feeds.html`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `7Wate, a180285`
- Source Location: `feeds.ts`
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
  - `www.foreverblog.cn/feeds.html`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/foreverblog/feeds",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 621,
  "location": "feeds.ts",
  "maintainers": [
    "7Wate",
    "a180285"
  ],
  "name": "专题展示 - 文章",
  "parameters": {},
  "path": "/feeds",
  "radar": [
    {
      "source": [
        "www.foreverblog.cn/feeds.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "十年之约——专题展示 - Powered by RSSHub",
      "errorAt": "2026-10-03T14:18:47.464Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "53110725864198144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.foreverblog.cn/feeds.html",
      "title": "十年之约——专题展示",
      "type": "feed",
      "url": "rsshub://foreverblog/feeds"
    }
  ],
  "url": "www.foreverblog.cn/feeds.html"
}
```
