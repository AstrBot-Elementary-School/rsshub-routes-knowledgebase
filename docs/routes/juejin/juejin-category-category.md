# 掘金 - 分类

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/juejin/category/:category`
- Route Name: `分类`
- Example: `/juejin/category/frontend`
- URL: `juejin.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `DIYgod`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 后端    | 前端     | Android | iOS | 人工智能 | 开发工具 | 代码人生 | 阅读    |
| ------- | -------- | ------- | --- | -------- | -------- | -------- | ------- |
| backend | frontend | android | ios | ai       | freebie  | career   | article |

## Parameters
- `category`: 分类名


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
  - `juejin.cn/:category`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 后端    | 前端     | Android | iOS | 人工智能 | 开发工具 | 代码人生 | 阅读    |\n| ------- | -------- | ------- | --- | -------- | -------- | -------- | ------- |\n| backend | frontend | android | ios | ai       | freebie  | career   | article |",
  "example": "/juejin/category/frontend",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1203,
  "location": "category.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类名"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "juejin.cn/:category"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "掘金 前端 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42107264805507072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://juejin.cn/frontend",
      "title": "掘金 前端",
      "type": "feed",
      "url": "rsshub://juejin/category/frontend"
    },
    {
      "description": "掘金 人工智能 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42000866869432330",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://juejin.cn/ai",
      "title": "掘金 人工智能",
      "type": "feed",
      "url": "rsshub://juejin/category/ai"
    }
  ]
}
```
