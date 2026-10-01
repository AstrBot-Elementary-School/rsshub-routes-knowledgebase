# Bangumi 番组计划 - 现实人物的新作品

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/bangumi.tv/person/:id`
- Route Name: `现实人物的新作品`
- Example: `/bangumi.tv/person/32943`
- URL: `bangumi.tv`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `ylc395`
- Source Location: `person/index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 人物 id, 在人物页面的地址栏查看


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
  - `bgm.tv/person/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bangumi.tv/person/32943",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "person/index.ts",
  "maintainers": [
    "ylc395"
  ],
  "name": "现实人物的新作品",
  "parameters": {
    "id": "人物 id, 在人物页面的地址栏查看"
  },
  "path": "/person/:id",
  "radar": [
    {
      "source": [
        "bgm.tv/person/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "MADHOUSE参与的作品 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "162840790478820352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgm.tv/person/603/works?sort=date",
      "title": "MADHOUSE参与的作品",
      "type": "feed",
      "url": "rsshub://bangumi.tv/person/603"
    },
    {
      "description": "STUDIO 4℃参与的作品 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "162841047287123968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bgm.tv/person/2306/works?sort=date",
      "title": "STUDIO 4℃参与的作品",
      "type": "feed",
      "url": "rsshub://bangumi.tv/person/2306"
    }
  ]
}
```
