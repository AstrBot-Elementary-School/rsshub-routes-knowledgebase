# 东方网 - 上海新闻

## Coverage
`index-only`

## Route
- Namespace: `eastday`
- Namespace Name: `东方网`
- Route Path: `/eastday/sh`
- Route Name: `上海新闻`
- Example: `/eastday/sh`
- URL: `sh.eastday.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `saury`
- Source Location: `sh.ts`
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
  - `sh.eastday.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/eastday/sh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 18,
  "location": "sh.ts",
  "maintainers": [
    "saury"
  ],
  "name": "上海新闻",
  "parameters": {},
  "path": "/sh",
  "radar": [
    {
      "source": [
        "sh.eastday.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "东方网-上海 - Powered by RSSHub",
      "errorAt": "2026-04-18T09:38:01.079Z",
      "errorMessage": "[GET] \"https://apin.eastday.com/apiplus/special/specialnewslistbyurl?specialUrl=1632798465040016&skipCount=0&limitCount=20\": 403 Forbidden\n",
      "id": "60975269249526784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://wap.eastday.com/wap/sh.html",
      "title": "东方网-上海",
      "type": "feed",
      "url": "rsshub://eastday/sh"
    }
  ],
  "url": "sh.eastday.com/"
}
```
