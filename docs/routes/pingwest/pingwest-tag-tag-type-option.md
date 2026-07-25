# 品玩 - 话题动态

## Coverage
`index-only`

## Route
- Namespace: `pingwest`
- Namespace Name: `品玩`
- Route Path: `/pingwest/tag/:tag/:type/:option?`
- Route Name: `话题动态`
- Example: `/pingwest/tag/ChinaJoy/1`
- URL: `pingwest.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `sanmmm`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
内容类型

| 最新 | 热门 |
| ---- | ---- |
| 1    | 2    |

参数

- `fulltext`，全文输出，例如：`/pingwest/tag/ChinaJoy/1/fulltext`

::: tip
该路由一次最多显示 30 条文章
:::

## Parameters
- `tag`: 话题名或话题id, 可从话题页url中得到
- `type`: 内容类型
- `option`: 参数, 默认无


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
    "new-media"
  ],
  "description": "内容类型\n\n| 最新 | 热门 |\n| ---- | ---- |\n| 1    | 2    |\n\n参数\n\n- `fulltext`，全文输出，例如：`/pingwest/tag/ChinaJoy/1/fulltext`\n\n::: tip\n该路由一次最多显示 30 条文章\n:::",
  "example": "/pingwest/tag/ChinaJoy/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 19,
  "location": "tag.ts",
  "maintainers": [
    "sanmmm"
  ],
  "name": "话题动态",
  "parameters": {
    "option": "参数, 默认无",
    "tag": "话题名或话题id, 可从话题页url中得到",
    "type": "内容类型"
  },
  "path": "/tag/:tag/:type/:option?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "品玩 - AIGC - Powered by RSSHub",
      "errorAt": "2026-05-25T10:17:17.755Z",
      "errorMessage": "[GET] \"https://www.pingwest.com/api/tag_article_list?id=20327&type=0\": 405 Not Allowed\n",
      "id": "85680099374822413",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pingwest.com/tag/20327",
      "title": "品玩 - AIGC",
      "type": "feed",
      "url": "rsshub://pingwest/tag/20327/1/fulltext"
    },
    {
      "description": "品玩 - ChinaJoy - Powered by RSSHub",
      "errorAt": "2026-06-24T11:21:51.460Z",
      "errorMessage": "[GET] \"https://www.pingwest.com/api/tag_article_list?id=7604&type=0\": 405 Not Allowed\n",
      "id": "69704836086005760",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pingwest.com/tag/ChinaJoy",
      "title": "品玩 - ChinaJoy",
      "type": "feed",
      "url": "rsshub://pingwest/tag/ChinaJoy/1"
    }
  ]
}
```
