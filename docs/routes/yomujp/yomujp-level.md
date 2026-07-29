# 日本語多読道場 - 等级

## Coverage
`index-only`

## Route
- Namespace: `yomujp`
- Namespace Name: `日本語多読道場`
- Route Path: `/yomujp/:level?`
- Route Name: `等级`
- Example: `/yomujp/n1`
- URL: `yomujp.com/`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `eternasuno`
- Source Location: `level.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `level`: 等级，n1~n6，为空默认全部


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
  - `yomujp.com/`
  - `yomujp.com/:level`
- `target`: `/:level`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/yomujp/n1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 103,
  "location": "level.ts",
  "maintainers": [
    "eternasuno"
  ],
  "name": "等级",
  "parameters": {
    "level": "等级，n1~n6，为空默认全部"
  },
  "path": "/:level?",
  "radar": [
    {
      "source": [
        "yomujp.com/",
        "yomujp.com/:level"
      ],
      "target": "/:level"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "みなさん、こんにちは。 「 日本語多読道場(にほんごたどくどうじょう) Yomujp」は日本語を勉強する人のための読みものサイト（website）です。 日本の地理、食べもの、動物、植物、文化や歴史などを紹介します。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81626287407283200",
      "image": "https://yomujp.com/wp-content/uploads/2023/08/top1-2-300x99-1.png",
      "ownerUserId": null,
      "siteUrl": "https://yomujp.com/",
      "title": "日本語多読道場",
      "type": "feed",
      "url": "rsshub://yomujp"
    },
    {
      "description": "みなさん、こんにちは。 「 日本語多読道場(にほんごたどくどうじょう) Yomujp」は日本語を勉強する人のための読みものサイト（website）です。 日本の地理、食べもの、動物、植物、文化や歴史などを紹介します。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70075032004540416",
      "image": "https://yomujp.com/wp-content/uploads/2023/08/top1-2-300x99-1.png",
      "ownerUserId": null,
      "siteUrl": "https://yomujp.com/n1",
      "title": "N1 | 日本語多読道場",
      "type": "feed",
      "url": "rsshub://yomujp/n1"
    }
  ],
  "url": "yomujp.com/"
}
```
