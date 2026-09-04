# 哔哩哔哩 bilibili - 入站必刷

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/precious/:embed?`
- Route Name: `入站必刷`
- Example: `/bilibili/precious`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `liuyuhe666`
- Source Location: `bilibili-recommend.ts`
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
  "example": "/bilibili/precious",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 83,
  "location": "bilibili-recommend.ts",
  "maintainers": [
    "liuyuhe666"
  ],
  "name": "入站必刷",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭"
  },
  "path": "/precious/:embed?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "哔哩哔哩入站必刷 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57230569101370368",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/v/popular/history",
      "title": "哔哩哔哩入站必刷",
      "type": "feed",
      "url": "rsshub://bilibili/precious"
    },
    {
      "description": "哔哩哔哩入站必刷 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69361213069277184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/v/popular/history",
      "title": "哔哩哔哩入站必刷",
      "type": "feed",
      "url": "rsshub://bilibili/precious/:disableEmbed"
    }
  ]
}
```
