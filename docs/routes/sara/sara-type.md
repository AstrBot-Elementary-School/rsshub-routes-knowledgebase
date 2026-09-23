# 上海业余无线电协会 - 新闻资讯

## Coverage
`index-only`

## Route
- Namespace: `sara`
- Namespace Name: `上海业余无线电协会`
- Route Path: `/sara/:type`
- Route Name: `新闻资讯`
- Example: `/sara/announcement`
- URL: `www.sara.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `HChenZi`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 协会动态 | 通知公告     | 行业动态 |
| -------- | ------------ | -------- |
| dynamic  | announcement | industry |

## Parameters
- `type`: dynamic | announcement | industry


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
    "government"
  ],
  "description": "| 协会动态 | 通知公告     | 行业动态 |\n| -------- | ------------ | -------- |\n| dynamic  | announcement | industry |",
  "example": "/sara/announcement",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "index.ts",
  "maintainers": [
    "HChenZi"
  ],
  "name": "新闻资讯",
  "parameters": {
    "type": "dynamic | announcement | industry"
  },
  "path": "/:type",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63520367990283267",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.sara.org.cn/news/announcement.htm",
      "title": "通知公告",
      "type": "feed",
      "url": "rsshub://sara/announcement"
    }
  ]
}
```
