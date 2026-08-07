# 阿里云 - 公告

## Coverage
`index-only`

## Route
- Namespace: `aliyun`
- Namespace Name: `阿里云`
- Route Path: `/aliyun/notice/:type?`
- Route Name: `公告`
- Example: `/aliyun/notice`
- URL: `developer.aliyun.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `muzea`
- Source Location: `notice.ts`
- Source Module: `_None_`

## Description
| 类型     | type |
| -------- | ---- |
| 全部     |      |
| 升级公告 | 1    |
| 安全公告 | 2    |
| 备案公告 | 3    |
| 其他     | 4    |

## Parameters
- `type`: N


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
    "programming"
  ],
  "description": "| 类型     | type |\n| -------- | ---- |\n| 全部     |      |\n| 升级公告 | 1    |\n| 安全公告 | 2    |\n| 备案公告 | 3    |\n| 其他     | 4    |",
  "example": "/aliyun/notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "notice.ts",
  "maintainers": [
    "muzea"
  ],
  "name": "公告",
  "parameters": {
    "type": "N"
  },
  "path": "/notice/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-19T18:19:06.546Z",
      "errorMessage": "Failed to fetch\n",
      "id": "147300396517260349",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://aliyun/notice/2"
    }
  ]
}
```
