# 大眼仔旭 - 分类

## Coverage
`index-only`

## Route
- Namespace: `dayanzai`
- Namespace Name: `大眼仔旭`
- Route Path: `/dayanzai/:category/:fulltext?`
- Route Name: `分类`
- Example: `/dayanzai/windows`
- URL: `dayanzai.me`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `gl0zzy`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 微软应用 | 安卓应用 | 教程资源 | 其他资源 |
| -------- | -------- | -------- | -------- |
| windows  | android  | tutorial | other    |

## Parameters
- `category`: 分类
- `fulltext`: 是否获取全文，需要获取则传入参数`y`


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
  - `dayanzai.me/:category`
  - `dayanzai.me/:category/*`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "| 微软应用 | 安卓应用 | 教程资源 | 其他资源 |\n| -------- | -------- | -------- | -------- |\n| windows  | android  | tutorial | other    |",
  "example": "/dayanzai/windows",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 118,
  "location": "index.ts",
  "maintainers": [
    "gl0zzy"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类",
    "fulltext": "是否获取全文，需要获取则传入参数`y`"
  },
  "path": "/:category/:fulltext?",
  "radar": [
    {
      "source": [
        "dayanzai.me/:category",
        "dayanzai.me/:category/*"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "大眼仔旭 windows RSS - Powered by RSSHub",
      "errorAt": "2025-12-19T05:39:37.981Z",
      "errorMessage": "[GET] \"http://www.dayanzai.me/windows\": <no response> fetch failed (Connect Timeout Error (attempted address: www.dayanzai.me:80, timeout: 10000ms))\n[GET] \"http://www.dayanzai.me/windows\": <no response> fetch failed\n502 \n[GET] \"http://www.dayanzai.me/windows\": <no response> fetch failed (Connect Timeout Error (attempted address: www.dayanzai.me:80, timeout: 10000ms))\n",
      "id": "64953399235565578",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.dayanzai.me/windows",
      "title": "大眼仔旭 windows",
      "type": "feed",
      "url": "rsshub://dayanzai/windows"
    },
    {
      "description": "大眼仔旭 android RSS - Powered by RSSHub",
      "errorAt": "2025-09-26T01:57:15.388Z",
      "errorMessage": "[GET] \"http://www.dayanzai.me/android\": <no response> fetch failed (Connect Timeout Error (attempted address: www.dayanzai.me:80, timeout: 10000ms))\n502 \n[GET] \"http://www.dayanzai.me/android\": <no response> fetch failed (Connect Timeout Error (attempted address: www.dayanzai.me:80, timeout: 10000ms))\n",
      "id": "66737530237513741",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.dayanzai.me/android",
      "title": "大眼仔旭 android",
      "type": "feed",
      "url": "rsshub://dayanzai/android"
    }
  ]
}
```
