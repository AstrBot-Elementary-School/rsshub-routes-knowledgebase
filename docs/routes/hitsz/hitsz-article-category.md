# 哈尔滨工业大学（深圳） - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `hitsz`
- Namespace Name: `哈尔滨工业大学（深圳）`
- Route Path: `/hitsz/article/:category?`
- Route Name: `新闻中心`
- Example: `/hitsz/article/id-74`
- URL: `hitsz.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `xandery-geek`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
| 校区要闻 | 媒体报道 | 综合新闻 | 校园动态 | 讲座论坛 | 热点专题 | 招标信息 | 重要关注 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| id-116   | id-80    | id-75    | id-77    | id-78    | id-79    | id-81    | id-124   |

## Parameters
- `category`: 分类名，默认为校园动态


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
    "university"
  ],
  "description": "| 校区要闻 | 媒体报道 | 综合新闻 | 校园动态 | 讲座论坛 | 热点专题 | 招标信息 | 重要关注 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| id-116   | id-80    | id-75    | id-77    | id-78    | id-79    | id-81    | id-124   |",
  "example": "/hitsz/article/id-74",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "article.ts",
  "maintainers": [
    "xandery-geek"
  ],
  "name": "新闻中心",
  "parameters": {
    "category": "分类名，默认为校园动态"
  },
  "path": "/article/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "哈尔滨工业大学（深圳）-校区要闻 - Powered by RSSHub",
      "errorAt": "2025-12-26T14:31:26.531Z",
      "errorMessage": "[GET] \"https://www.hitsz.edu.cn/article/id-116.html\": 404 Not Found\n",
      "id": "163581729920492544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hitsz.edu.cn/article/id-116.html",
      "title": "哈尔滨工业大学（深圳）-校区要闻",
      "type": "feed",
      "url": "rsshub://hitsz/article/id-116"
    }
  ]
}
```
