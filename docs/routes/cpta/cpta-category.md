# 中国人事考试网 - 中国人事考试网发布

## Coverage
`index-only`

## Route
- Namespace: `cpta`
- Namespace Name: `中国人事考试网`
- Route Path: `/cpta/:category`
- Route Name: `中国人事考试网发布`
- Example: `/cpta/notice`
- URL: `www.cpta.com.cn`
- Language: `_None_`
- Categories: `study`
- Maintainers: `PrinOrange`
- Source Location: `handler.ts`
- Source Module: `_None_`

## Description
| Category    | Title    | Description                     |
| ----------- | -------- | ------------------------------- |
| notice      | 通知公告 | 中国人事考试网 考试通知公告汇总 |
| performance | 成绩公布 | 中国人事考试网 考试成绩公布汇总 |

## Parameters
- `category`: 栏目参数，可见下表描述。


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true
- `antiCrawler`: true

## Radar
### Rule 1
- `title`: `中国人事考试网通知公告`
- `source`:
  - `www.cpta.com.cn/notice.html`
  - `www.cpta.com.cn`
- `target`: `/notice`
### Rule 2
- `title`: `中国人事考试网成绩发布`
- `source`:
  - `www.cpta.com.cn/performance.html`
  - `www.cpta.com.cn`
- `target`: `/performance`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| Category    | Title    | Description                     |\n| ----------- | -------- | ------------------------------- |\n| notice      | 通知公告 | 中国人事考试网 考试通知公告汇总 |\n| performance | 成绩公布 | 中国人事考试网 考试成绩公布汇总 |",
  "example": "/cpta/notice",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 27,
  "location": "handler.ts",
  "maintainers": [
    "PrinOrange"
  ],
  "name": "中国人事考试网发布",
  "parameters": {
    "category": "栏目参数，可见下表描述。"
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "www.cpta.com.cn/notice.html",
        "www.cpta.com.cn"
      ],
      "target": "/notice",
      "title": "中国人事考试网通知公告"
    },
    {
      "source": [
        "www.cpta.com.cn/performance.html",
        "www.cpta.com.cn"
      ],
      "target": "/performance",
      "title": "中国人事考试网成绩发布"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中国人事考试网 考试通知公告汇总 - Powered by RSSHub",
      "errorAt": "2025-11-06T18:02:50.011Z",
      "errorMessage": "[GET] \"http://www.cpta.com.cn/notice.html\": 405 Not Allowed\n",
      "id": "101869703891043328",
      "image": "https://www.gov.cn/images/gtrs_logo_lt.png",
      "ownerUserId": null,
      "siteUrl": "http://www.cpta.com.cn/notice.html",
      "title": "中国人事考试网-通知公告",
      "type": "feed",
      "url": "rsshub://cpta/notice"
    },
    {
      "description": "中国人事考试网 考试成绩公布汇总 - Powered by RSSHub",
      "errorAt": "2025-05-30T12:00:11.935Z",
      "errorMessage": "[GET] \"http://www.cpta.com.cn/performance.html\": 405 Not Allowed\n",
      "id": "105272910866823168",
      "image": "https://www.gov.cn/images/gtrs_logo_lt.png",
      "ownerUserId": null,
      "siteUrl": "http://www.cpta.com.cn/performance.html",
      "title": "中国人事考试网-成绩公布",
      "type": "feed",
      "url": "rsshub://cpta/performance"
    }
  ]
}
```
