# 极术社区 - 频道、专栏、用户

## Coverage
`index-only`

## Route
- Namespace: `aijishu`
- Namespace Name: `极术社区`
- Route Path: `/aijishu/:type/:name?`
- Route Name: `频道、专栏、用户`
- Example: `/aijishu/channel/ai`
- URL: `www.aijishu`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `bigfei`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| type    | 说明 |
| ------- | ---- |
| channel | 频道 |
| blog    | 专栏 |
| u       | 用户 |

## Parameters
- `type`: 文章类型，可以取值如下
- `name`: 名字，取自URL


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
  "description": "| type    | 说明 |\n| ------- | ---- |\n| channel | 频道 |\n| blog    | 专栏 |\n| u       | 用户 |",
  "example": "/aijishu/channel/ai",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "index.ts",
  "maintainers": [
    "bigfei"
  ],
  "name": "频道、专栏、用户",
  "parameters": {
    "name": "名字，取自URL",
    "type": "文章类型，可以取值如下"
  },
  "path": "/:type/:name?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-08-06T08:03:32.932Z",
      "errorMessage": "[GET] \"https://aijishu.com/channel/ai\": 404 Not Found\n",
      "id": "175826160368390153",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://aijishu/channel/ai"
    },
    {
      "description": null,
      "errorAt": "2026-05-11T03:02:37.106Z",
      "errorMessage": "[GET] \"https://aijishu.comundefined?page=1\": <no response> fetch failed (getaddrinfo ENOTFOUND aijishu.comundefined)\n",
      "id": "250564935356404739",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://aijishu/hot"
    }
  ]
}
```
