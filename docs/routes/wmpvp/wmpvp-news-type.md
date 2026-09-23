# 完美世界电竞 - 资讯列表

## Coverage
`index-only`

## Route
- Namespace: `wmpvp`
- Namespace Name: `完美世界电竞`
- Route Path: `/wmpvp/news/:type`
- Route Name: `资讯列表`
- Example: `/wmpvp/news/1`
- URL: `wmpvp.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `tssujt`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| DOTA2 | CS2 |
| ----- | --- |
| 1     | 2   |

## Parameters
- `type`: 资讯分类，见下表


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
    "game"
  ],
  "description": "| DOTA2 | CS2 |\n| ----- | --- |\n| 1     | 2   |",
  "example": "/wmpvp/news/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 69,
  "location": "index.ts",
  "maintainers": [
    "tssujt"
  ],
  "name": "资讯列表",
  "parameters": {
    "type": "资讯分类，见下表"
  },
  "path": "/news/:type",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "完美世界电竞 - CS2 资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71465854017649664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.wmpvp.com/",
      "title": "完美世界电竞 - CS2 资讯",
      "type": "feed",
      "url": "rsshub://wmpvp/news/2"
    },
    {
      "description": "完美世界电竞 - DOTA2 资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59123449172993025",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.wmpvp.com/",
      "title": "完美世界电竞 - DOTA2 资讯",
      "type": "feed",
      "url": "rsshub://wmpvp/news/1"
    }
  ]
}
```
