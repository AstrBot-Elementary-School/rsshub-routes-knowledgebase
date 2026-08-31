# 南京大学 - 大学外语部

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/nju/dafls`
- Route Name: `大学外语部`
- Example: `/nju/dafls`
- URL: `dafls.nju.edu.cn/13167/list.html`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ret-1`
- Source Location: `dafls.ts`
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
  - `dafls.nju.edu.cn/13167/list.html`
  - `dafls.nju.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/nju/dafls",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "dafls.ts",
  "maintainers": [
    "ret-1"
  ],
  "name": "大学外语部",
  "parameters": {},
  "path": "/dafls",
  "radar": [
    {
      "source": [
        "dafls.nju.edu.cn/13167/list.html",
        "dafls.nju.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "大外部-通知公告 - Powered by RSSHub",
      "errorAt": "2025-12-03T06:46:07.911Z",
      "errorMessage": "[GET] \"https://dafls.nju.edu.cn/13167/list.htm\": <no response> fetch failed\n",
      "id": "62660338104085504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://dafls.nju.edu.cn/13167/list.htm",
      "title": "大外部-通知公告",
      "type": "feed",
      "url": "rsshub://nju/dafls"
    }
  ],
  "url": "dafls.nju.edu.cn/13167/list.html"
}
```
