# Blue Archive - News

## Coverage
`index-only`

## Route
- Namespace: `bluearchive`
- Namespace Name: `Blue Archive`
- Route Path: `/bluearchive/news/:server/:type?`
- Route Name: `News`
- Example: `/bluearchive/news/jp`
- URL: `bluearchive.jp`
- Language: `_None_`
- Categories: `game`
- Maintainers: `equt`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 全て | イベント | お知らせ | メンテナンス |
| :--: | :--: | :--: | :--: |
| 0 | 1 | 2 | 3 |

## Parameters
- `server`: game server (ISO 3166 two-letter country code, case-insensitive), only `JP` is supported for now
- `type`: news type, checkout the table below for details


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
  "description": "| 全て | イベント | お知らせ | メンテナンス |\n| :--: | :--: | :--: | :--: |\n| 0 | 1 | 2 | 3 |",
  "example": "/bluearchive/news/jp",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "news.ts",
  "maintainers": [
    "equt"
  ],
  "name": "News",
  "parameters": {
    "server": "game server (ISO 3166 two-letter country code, case-insensitive), only `JP` is supported for now",
    "type": "news type, checkout the table below for details"
  },
  "path": "/news/:server/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "ブルアカ - 全て - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86033006654854144",
      "image": "https://webcnstatic.yostar.net/ba_cn_web/prod/web/favicon.png",
      "ownerUserId": null,
      "siteUrl": "https://bluearchive.jp/news/newsJump",
      "title": "ブルアカ - 全て",
      "type": "feed",
      "url": "rsshub://bluearchive/news/jp"
    }
  ]
}
```
