# 豆瓣 - 浏览发现

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/explore`
- Route Name: `浏览发现`
- Example: `/douban/explore`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `clarkzsd`
- Source Location: `other/explore.tsx`
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
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douban/explore",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "other/explore.tsx",
  "maintainers": [
    "clarkzsd"
  ],
  "name": "浏览发现",
  "parameters": {},
  "path": "/explore",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "豆瓣-浏览发现 - Powered by RSSHub",
      "errorAt": "2024-10-29T09:52:15.307Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "53908061985105943",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.douban.com/explore",
      "title": "豆瓣-浏览发现",
      "type": "feed",
      "url": "rsshub://douban/explore"
    }
  ]
}
```
