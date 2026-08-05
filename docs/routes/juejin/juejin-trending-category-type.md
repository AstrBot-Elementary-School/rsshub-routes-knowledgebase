# 掘金 - 热门

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/juejin/trending/:category/:type`
- Route Name: `热门`
- Example: `/juejin/trending/ios/monthly`
- URL: `juejin.cn`
- Language: `_None_`
- Categories: `programming, popular`
- Maintainers: `moaix`
- Source Location: `trending.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "all", "description": "分类名", "options": [{"label": "Android", "value": "android"}, {"label": "前端", "value": "frontend"}, {"label": "iOS", "value": "ios"}, {"label": "后端", "value": "backend"}, {"label": "设计", "value": "design"}, {"label": "产品", "value": "product"}, {"label": "工具资源", "value": "freebie"}, {"label": "阅读", "value": "article"}, {"label": "人工智能", "value": "ai"}, {"label": "运维", "value": "devops"}, {"label": "全部", "value": "all"}]}
- `type`: {"default": "weekly", "description": "类型", "options": [{"label": "本周最热", "value": "weekly"}, {"label": "本月最热", "value": "monthly"}, {"label": "历史最热", "value": "historical"}]}


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
    "programming",
    "popular"
  ],
  "example": "/juejin/trending/ios/monthly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5476,
  "location": "trending.ts",
  "maintainers": [
    "moaix"
  ],
  "name": "热门",
  "parameters": {
    "category": {
      "default": "all",
      "description": "分类名",
      "options": [
        {
          "label": "Android",
          "value": "android"
        },
        {
          "label": "前端",
          "value": "frontend"
        },
        {
          "label": "iOS",
          "value": "ios"
        },
        {
          "label": "后端",
          "value": "backend"
        },
        {
          "label": "设计",
          "value": "design"
        },
        {
          "label": "产品",
          "value": "product"
        },
        {
          "label": "工具资源",
          "value": "freebie"
        },
        {
          "label": "阅读",
          "value": "article"
        },
        {
          "label": "人工智能",
          "value": "ai"
        },
        {
          "label": "运维",
          "value": "devops"
        },
        {
          "label": "全部",
          "value": "all"
        }
      ]
    },
    "type": {
      "default": "weekly",
      "description": "类型",
      "options": [
        {
          "label": "本周最热",
          "value": "weekly"
        },
        {
          "label": "本月最热",
          "value": "monthly"
        },
        {
          "label": "历史最热",
          "value": "historical"
        }
      ]
    }
  },
  "path": "/trending/:category/:type",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "掘金本周最热 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56600299048345600",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://juejin.im/recommended?sort=weekly_hottest",
      "title": "掘金本周最热",
      "type": "feed",
      "url": "rsshub://juejin/trending/all/weekly"
    },
    {
      "description": "掘金前端本周最热 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55215029121101832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://juejin.im/frontend?sort=weekly_hottest",
      "title": "掘金前端本周最热",
      "type": "feed",
      "url": "rsshub://juejin/trending/frontend/weekly"
    }
  ]
}
```
