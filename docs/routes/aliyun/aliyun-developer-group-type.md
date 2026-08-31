# 阿里云 - 开发者社区 - 主题

## Coverage
`index-only`

## Route
- Namespace: `aliyun`
- Namespace Name: `阿里云`
- Route Path: `/aliyun/developer/group/:type`
- Route Name: `开发者社区 - 主题`
- Example: `/aliyun/developer/group/alitech`
- URL: `developer.aliyun.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `umm233`
- Source Location: `developer/group.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: 对应技术领域分类


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
  - `developer.aliyun.com/group/:type`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/aliyun/developer/group/alitech",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16,
  "location": "developer/group.ts",
  "maintainers": [
    "umm233"
  ],
  "name": "开发者社区 - 主题",
  "parameters": {
    "type": "对应技术领域分类"
  },
  "path": "/developer/group/:type",
  "radar": [
    {
      "source": [
        "developer.aliyun.com/group/:type"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "阿里云开发者社区- - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "163224149070041094",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://developer.aliyun.com/group/alitech",
      "title": "阿里云开发者社区-",
      "type": "feed",
      "url": "rsshub://aliyun/developer/group/alitech"
    }
  ]
}
```
