# 爱思想 - 排行

## Coverage
`index-only`

## Route
- Namespace: `aisixiang`
- Namespace Name: `爱思想`
- Route Path: `/aisixiang/toplist/:id?/:period?`
- Route Name: `排行`
- Example: `/aisixiang/toplist/1/7`
- URL: `aisixiang.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `HenryQW, nczitzk`
- Source Location: `toplist.ts`
- Source Module: `_None_`

## Description
| 文章点击排行 | 最近更新文章 | 文章推荐排行 |
| ------------ | ------------ | ------------ |
| 1            | 10           | 11           |

## Parameters
- `id`: 类型
- `period`: 范围, 仅适用于点击排行榜, 可选一天(1)，一周(7)，一月(30)，所有(-1)，默认为一天


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "| 文章点击排行 | 最近更新文章 | 文章推荐排行 |\n| ------------ | ------------ | ------------ |\n| 1            | 10           | 11           |",
  "example": "/aisixiang/toplist/1/7",
  "heat": 17,
  "location": "toplist.ts",
  "maintainers": [
    "HenryQW",
    "nczitzk"
  ],
  "name": "排行",
  "parameters": {
    "id": "类型",
    "period": "范围, 仅适用于点击排行榜, 可选一天(1)，一周(7)，一月(30)，所有(-1)，默认为一天"
  },
  "path": "/toplist/:id?/:period?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "爱思想 - 一天文章点击排行 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72974175979885568",
      "image": "https://oss.aisixiang.com/images/logo_toplist.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.aisixiang.com/toplist?id=1&period=1",
      "title": "爱思想 - 一天文章点击排行",
      "type": "feed",
      "url": "rsshub://aisixiang/toplist"
    },
    {
      "description": "爱思想 - 一周文章点击排行 - Powered by RSSHub",
      "errorAt": "2026-08-10T22:00:40.443Z",
      "errorMessage": "[GET] \"https://www.aisixiang.com/toplist?id=1&period=7\": <no response> fetch failed (Client network socket disconnected before secure TLS connection was established)\n",
      "id": "75338776503090177",
      "image": "https://oss.aisixiang.com/images/logo_toplist.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.aisixiang.com/toplist?id=1&period=7",
      "title": "爱思想 - 一周文章点击排行",
      "type": "feed",
      "url": "rsshub://aisixiang/toplist/1/7"
    }
  ]
}
```
