# 方格子 - 出版專題

## Coverage
`index-only`

## Route
- Namespace: `vocus`
- Namespace Name: `方格子`
- Route Path: `/vocus/publication/:id`
- Route Name: `出版專題`
- Example: `/vocus/publication/bass`
- URL: `vocus.cc`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Maecenas`
- Source Location: `publication.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 出版專題 id，可在出版專題主页的 URL 找到


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
  - `vocus.cc/:id/home`
  - `vocus.cc/:id/introduce`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/vocus/publication/bass",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "publication.ts",
  "maintainers": [
    "Maecenas"
  ],
  "name": "出版專題",
  "parameters": {
    "id": "出版專題 id，可在出版專題主页的 URL 找到"
  },
  "path": "/publication/:id",
  "radar": [
    {
      "source": [
        "vocus.cc/:id/home",
        "vocus.cc/:id/introduce"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "在我們的生活裡面，處處受到日本文化的影響。現在去日本旅遊的人眾多，也有許多漫畫及日劇受到大家的喜愛。 本專欄作者是日語老師，也是文化研究者。從輕鬆有趣的角度，解析日本文化及日語，並且教大家一些日語中的文化內涵。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69582989510702087",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://vocus.cc/jp-kyochiku/home",
      "title": "來從日本文化學日語 - 文章列表｜方格子 vocus",
      "type": "feed",
      "url": "rsshub://vocus/publication/jp-kyochiku"
    },
    {
      "description": "全世界都是向 Google 看，向臉書看，沒有人往矽谷的另一邊看。所以我要帶你看矽谷很少有人知道的另一面。矽谷不是你想的那樣。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "97674302849284096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://vocus.cc/bass/home",
      "title": "異類矽谷 - 文章列表｜方格子 vocus",
      "type": "feed",
      "url": "rsshub://vocus/publication/bass"
    }
  ]
}
```
