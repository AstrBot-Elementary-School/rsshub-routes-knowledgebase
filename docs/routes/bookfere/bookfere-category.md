# 书伴 - 分类

## Coverage
`index-only`

## Route
- Namespace: `bookfere`
- Namespace Name: `书伴`
- Route Path: `/bookfere/:category`
- Route Name: `分类`
- Example: `/bookfere/skills`
- URL: `bookfere.com`
- Language: `_None_`
- Categories: `reading, popular`
- Maintainers: `OdinZhang`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 每周一书 | 使用技巧 | 图书推荐 | 新闻速递 | 精选短文 |
| -------- | -------- | -------- | -------- | -------- |
| weekly   | skills   | books    | news     | essay    |

## Parameters
- `category`: {"description": "分类名", "options": [{"label": "每周一书", "value": "weekly"}, {"label": "使用技巧", "value": "skills"}, {"label": "图书推荐", "value": "books"}, {"label": "新闻速递", "value": "news"}, {"label": "精选短文", "value": "essay"}]}


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
    "reading",
    "popular"
  ],
  "description": "| 每周一书 | 使用技巧 | 图书推荐 | 新闻速递 | 精选短文 |\n| -------- | -------- | -------- | -------- | -------- |\n| weekly   | skills   | books    | news     | essay    |",
  "example": "/bookfere/skills",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3433,
  "location": "category.ts",
  "maintainers": [
    "OdinZhang"
  ],
  "name": "分类",
  "parameters": {
    "category": {
      "description": "分类名",
      "options": [
        {
          "label": "每周一书",
          "value": "weekly"
        },
        {
          "label": "使用技巧",
          "value": "skills"
        },
        {
          "label": "图书推荐",
          "value": "books"
        },
        {
          "label": "新闻速递",
          "value": "news"
        },
        {
          "label": "精选短文",
          "value": "essay"
        }
      ]
    }
  },
  "path": "/:category",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "每周一书 – 书伴 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68570312983970816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bookfere.com/category/weekly",
      "title": "每周一书 – 书伴",
      "type": "feed",
      "url": "rsshub://bookfere/weekly"
    },
    {
      "description": "图书推荐 – 书伴 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72507626829125632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bookfere.com/category/books",
      "title": "图书推荐 – 书伴",
      "type": "feed",
      "url": "rsshub://bookfere/books"
    }
  ],
  "view": 0
}
```
