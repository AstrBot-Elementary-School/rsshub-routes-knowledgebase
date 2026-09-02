# 少数派 sspai - 专栏

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/sspai/column/:id`
- Route Name: `专栏`
- Example: `/sspai/column/262`
- URL: `sspai.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `LogicJake`
- Source Location: `column.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 专栏 id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `sspai.com/column/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/column/262",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 116,
  "location": "column.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "专栏",
  "parameters": {
    "id": "专栏 id"
  },
  "path": "/column/:id",
  "radar": [
    {
      "source": [
        "sspai.com/column/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "追求可持续生产力 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69021638026256389",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/column/266",
      "title": "少数派专栏-生产力周报",
      "type": "feed",
      "url": "rsshub://sspai/column/266"
    },
    {
      "description": "分享科研、教学日常中使用的工具与技术 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57815560000316416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/column/245",
      "title": "少数派专栏-科研利器",
      "type": "feed",
      "url": "rsshub://sspai/column/245"
    }
  ]
}
```
