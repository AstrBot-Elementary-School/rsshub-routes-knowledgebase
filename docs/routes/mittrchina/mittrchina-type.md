# 麻省理工科技评论 - 首页

## Coverage
`index-only`

## Route
- Namespace: `mittrchina`
- Namespace Name: `麻省理工科技评论`
- Route Path: `/mittrchina/:type?`
- Route Name: `首页`
- Example: `/mittrchina/index`
- URL: `mittrchina.com`
- Language: `_None_`
- Categories: `new-media, popular`
- Maintainers: `EsuRt, queensferryme`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| 快讯     | 本周热文 | 首页资讯 | 视频  |
| -------- | -------- | -------- | ----- |
| breaking | hot      | index    | video |

## Parameters
- `type`: 类型，见下表，默认为首页资讯


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
    "new-media",
    "popular"
  ],
  "description": "| 快讯     | 本周热文 | 首页资讯 | 视频  |\n| -------- | -------- | -------- | ----- |\n| breaking | hot      | index    | video |",
  "example": "/mittrchina/index",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1713,
  "location": "index.tsx",
  "maintainers": [
    "EsuRt",
    "queensferryme"
  ],
  "name": "首页",
  "parameters": {
    "type": "类型，见下表，默认为首页资讯"
  },
  "path": "/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "MIT 科技评论 - 首页资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71796886442021888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mittrchina.com/index",
      "title": "MIT 科技评论 - 首页资讯",
      "type": "feed",
      "url": "rsshub://mittrchina"
    },
    {
      "description": "MIT 科技评论 - 本周热榜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41492096674907158",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mittrchina.com/hot",
      "title": "MIT 科技评论 - 本周热榜",
      "type": "feed",
      "url": "rsshub://mittrchina/hot"
    }
  ]
}
```
