# 安全客 - 分类订阅

## Coverage
`index-only`

## Route
- Namespace: `anquanke`
- Namespace Name: `安全客`
- Route Path: `/anquanke/:category/:fulltext?`
- Route Name: `分类订阅`
- Example: `/anquanke/week`
- URL: `anquanke.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `qwertyuiop6`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 360 网络安全周报 | 活动     | 知识      | 资讯 | 招聘 | 工具 |
| ---------------- | -------- | --------- | ---- | ---- | ---- |
| week             | activity | knowledge | news | job  | tool |

## Parameters
- `category`: 分类订阅
- `fulltext`: 是否获取全文，如需获取全文参数传入 `quanwen` 或 `fulltext`


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
  "description": "| 360 网络安全周报 | 活动     | 知识      | 资讯 | 招聘 | 工具 |\n| ---------------- | -------- | --------- | ---- | ---- | ---- |\n| week             | activity | knowledge | news | job  | tool |",
  "example": "/anquanke/week",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 104,
  "location": "category.ts",
  "maintainers": [
    "qwertyuiop6"
  ],
  "name": "分类订阅",
  "parameters": {
    "category": "分类订阅",
    "fulltext": "是否获取全文，如需获取全文参数传入 `quanwen` 或 `fulltext`"
  },
  "path": "/:category/:fulltext?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "安全客-360网络安全周报 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56283113559261184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.anquanke.com/week-list",
      "title": "安全客-360网络安全周报",
      "type": "feed",
      "url": "rsshub://anquanke/week"
    },
    {
      "description": "安全客-安全知识 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "76187233397022720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.anquanke.com/knowledge",
      "title": "安全客-安全知识",
      "type": "feed",
      "url": "rsshub://anquanke/knowledge"
    }
  ]
}
```
