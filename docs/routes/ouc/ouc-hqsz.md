# 中国海洋大学 - 后勤公告通知

## Coverage
`index-only`

## Route
- Namespace: `ouc`
- Namespace Name: `中国海洋大学`
- Route Path: `/ouc/hqsz`
- Route Name: `后勤公告通知`
- Example: `/ouc/hqsz`
- URL: `hqsz.ouc.edu.cn/news.html?typeId=02`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ladeng07`
- Source Location: `hqsz.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `hqsz.ouc.edu.cn/news.html`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/ouc/hqsz",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "hqsz.ts",
  "maintainers": [
    "ladeng07"
  ],
  "name": "后勤公告通知",
  "parameters": {},
  "path": "/hqsz",
  "radar": [
    {
      "source": [
        "hqsz.ouc.edu.cn/news.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "hqsz.ouc.edu.cn/news.html?typeId=02"
}
```
