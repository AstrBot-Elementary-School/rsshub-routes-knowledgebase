# 广州日报 - 客户端

## Coverage
`index-only`

## Route
- Namespace: `gzdaily`
- Namespace Name: `广州日报`
- Route Path: `/gzdaily/app/:column?`
- Route Name: `客户端`
- Example: `/gzdaily/app/74`
- URL: `gzdaily.cn`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TimWu007`
- Source Location: `app.tsx`
- Source Module: `_None_`

## Description
::: tip
在北京时间深夜可能无法获取内容。
:::

常用栏目 ID：

| 栏目名 | ID   |
| ------ | ---- |
| 首页   | 74   |
| 时局   | 374  |
| 广州   | 371  |
| 大湾区 | 397  |
| 城区   | 2980 |

## Parameters
- `column`: 栏目 ID，点击对应栏目后在地址栏找到


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
    "traditional-media"
  ],
  "description": "::: tip\n在北京时间深夜可能无法获取内容。\n:::\n\n常用栏目 ID：\n\n| 栏目名 | ID   |\n| ------ | ---- |\n| 首页   | 74   |\n| 时局   | 374  |\n| 广州   | 371  |\n| 大湾区 | 397  |\n| 城区   | 2980 |",
  "example": "/gzdaily/app/74",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "app.tsx",
  "maintainers": [
    "TimWu007"
  ],
  "name": "客户端",
  "parameters": {
    "column": "栏目 ID，点击对应栏目后在地址栏找到"
  },
  "path": "/app/:column?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-10-12T16:28:11.870Z",
      "errorMessage": "[GET] \"https://app.gzdaily.cn/app_if/getArticles?columnId=74&page=1\": 405 Not Allowed\n",
      "id": "200235547707998211",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://gzdaily/app/74"
    }
  ]
}
```
