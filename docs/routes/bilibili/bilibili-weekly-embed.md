# 哔哩哔哩 bilibili - B 站每周必看

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/weekly/:embed?`
- Route Name: `B 站每周必看`
- Example: `/bilibili/weekly`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `ttttmr`
- Source Location: `weekly-recommend.ts`
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
    "social-media",
    "popular"
  ],
  "example": "/bilibili/weekly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3721,
  "location": "weekly-recommend.ts",
  "maintainers": [
    "ttttmr"
  ],
  "name": "B 站每周必看",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭"
  },
  "path": "/weekly/:embed?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "B站每周必看 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41461870197170192",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/h5/weekly-recommend",
      "title": "B站每周必看",
      "type": "feed",
      "url": "rsshub://bilibili/weekly"
    },
    {
      "description": "B站每周必看 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59798160460396544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bilibili.com/h5/weekly-recommend",
      "title": "B站每周必看",
      "type": "feed",
      "url": "rsshub://bilibili/weekly/:disableEmbed"
    }
  ]
}
```
