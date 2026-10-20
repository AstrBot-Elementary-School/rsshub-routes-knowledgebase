# 少数派 sspai - 付费专栏文章更新

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/sspai/series/:id`
- Route Name: `付费专栏文章更新`
- Example: `/sspai/series/77`
- URL: `sspai.com/series`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `series-update.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 专栏 id


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
  - `sspai.com/series/:id`
  - `sspai.com/series/:id/list`
  - `sspai.com/series/:id/metadata`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/series/77",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 41,
  "location": "series-update.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "付费专栏文章更新",
  "parameters": {
    "id": "专栏 id"
  },
  "path": "/series/:id",
  "radar": [
    {
      "source": [
        "sspai.com/series/:id",
        "sspai.com/series/:id/list",
        "sspai.com/series/:id/metadata"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "给知识工作者的 Notion 终极指南 - 少数派 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58422010972152832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/series/303",
      "title": "Notion All in One：搭建高能效率系统 - 少数派",
      "type": "feed",
      "url": "rsshub://sspai/series/303"
    },
    {
      "description": "分享租房的避坑经历和装修灵感。 - 少数派 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66512179166858240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/series/348",
      "title": "租来的好生活 - 少数派",
      "type": "feed",
      "url": "rsshub://sspai/series/348"
    }
  ],
  "url": "sspai.com/series"
}
```
