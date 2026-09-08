# 广东外语外贸大学 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `gdufs`
- Namespace Name: `广东外语外贸大学`
- Route Path: `/gdufs/news`
- Route Name: `新闻`
- Example: `/gdufs/news`
- URL: `www.gdufs.edu.cn/gwxw/gwxw1.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `gz4zzxc`
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
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.gdufs.edu.cn/gwxw/gwxw1.htm`
  - `www.gdufs.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/gdufs/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "news.ts",
  "maintainers": [
    "gz4zzxc"
  ],
  "name": "新闻",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.gdufs.edu.cn/gwxw/gwxw1.htm",
        "www.gdufs.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "广东外语外贸大学-大学要闻 - Powered by RSSHub",
      "errorAt": "2026-09-06T18:57:30.793Z",
      "errorMessage": "[GET] \"https://www.gdufs.edu.cn/gwxw/gwxw1.htm\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 202.116.196.186:443, 2001:da8:2003:12::5:443, timeout: 10000ms))\n",
      "id": "91668942959232000",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.gdufs.edu.cn/gwxw/gwxw1.htm",
      "title": "广外-大学要闻",
      "type": "feed",
      "url": "rsshub://gdufs/news"
    }
  ],
  "url": "www.gdufs.edu.cn/gwxw/gwxw1.htm"
}
```
