# PLAYNO.1 玩樂達人 - 情趣

## Coverage
`index-only`

## Route
- Namespace: `playno1`
- Namespace Name: `PLAYNO.1 玩樂達人`
- Route Path: `/playno1/st/:catid?`
- Route Name: `情趣`
- Example: `/playno1/st`
- URL: `stno1.playno1.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `st.ts`
- Source Module: `_None_`

## Description
| 全部文章 | 情趣體驗報告 | 情趣新聞 | 情趣研究所 |
| -------- | ------------ | -------- | ---------- |
| all      | experience   | news     | graduate   |

## Parameters
- `catid`: 分类，见下表，默认为全部文章


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
  - `stno1.playno1.com/stno1/:catid/`
- `target`: `/st/:catid`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| 全部文章 | 情趣體驗報告 | 情趣新聞 | 情趣研究所 |\n| -------- | ------------ | -------- | ---------- |\n| all      | experience   | news     | graduate   |",
  "example": "/playno1/st",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 199,
  "location": "st.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "情趣",
  "parameters": {
    "catid": "分类，见下表，默认为全部文章"
  },
  "path": "/st/:catid?",
  "radar": [
    {
      "source": [
        "stno1.playno1.com/stno1/:catid/"
      ],
      "target": "/st/:catid"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "情趣全部文章-情趣No.1-PLAYNO.1玩樂達人 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57752458090347520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://stno1.playno1.com/stno1/all/",
      "title": "情趣全部文章-情趣No.1-PLAYNO.1玩樂達人",
      "type": "feed",
      "url": "rsshub://playno1/st"
    },
    {
      "description": "情趣全部文章-情趣No.1-PLAYNO.1玩樂達人 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69537146680018944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://stno1.playno1.com/stno1/all/",
      "title": "情趣全部文章-情趣No.1-PLAYNO.1玩樂達人",
      "type": "feed",
      "url": "rsshub://playno1/st/all"
    }
  ]
}
```
