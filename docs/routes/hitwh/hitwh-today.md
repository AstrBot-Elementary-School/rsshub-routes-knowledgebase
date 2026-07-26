# 哈尔滨工业大学（威海） - 今日工大 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `hitwh`
- Namespace Name: `哈尔滨工业大学（威海）`
- Route Path: `/hitwh/today`
- Route Name: `今日工大 - 通知公告`
- Example: `/hitwh/today`
- URL: `hitwh.edu.cn/1024/list.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `raptazure`
- Source Location: `today.ts`
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
  - `hitwh.edu.cn/1024/list.htm`
  - `hitwh.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/hitwh/today",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "today.ts",
  "maintainers": [
    "raptazure"
  ],
  "name": "今日工大 - 通知公告",
  "parameters": {},
  "path": "/today",
  "radar": [
    {
      "source": [
        "hitwh.edu.cn/1024/list.htm",
        "hitwh.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "哈尔滨工业大学（威海）通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "88150334662734848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://today.hitwh.edu.cn/1024/list.htm",
      "title": "哈尔滨工业大学（威海）通知公告",
      "type": "feed",
      "url": "rsshub://hitwh/today"
    }
  ],
  "url": "hitwh.edu.cn/1024/list.htm"
}
```
