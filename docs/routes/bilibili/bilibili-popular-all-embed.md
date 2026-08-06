# 哔哩哔哩 bilibili - 综合热门

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/popular/all/:embed?`
- Route Name: `综合热门`
- Example: `/bilibili/popular/all`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `ziminliu`
- Source Location: `popular.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `embed`: 默认为开启内嵌视频, 任意值为关闭


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
    "social-media"
  ],
  "example": "/bilibili/popular/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 891,
  "location": "popular.ts",
  "maintainers": [
    "ziminliu"
  ],
  "name": "综合热门",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭"
  },
  "path": "/popular/all/:embed?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "bilibili 综合热门 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59083231910809602",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/",
      "title": "bilibili 综合热门",
      "type": "feed",
      "url": "rsshub://bilibili/popular/all"
    },
    {
      "description": "bilibili 综合热门 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "169231605189909504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/",
      "title": "bilibili 综合热门",
      "type": "feed",
      "url": "rsshub://bilibili/popular/all/1&limit=10"
    }
  ]
}
```
