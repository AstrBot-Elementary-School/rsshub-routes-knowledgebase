# Furstar - 画师列表

## Coverage
`index-only`

## Route
- Namespace: `furstar`
- Namespace Name: `Furstar`
- Route Path: `/furstar/artists/:lang?`
- Route Name: `画师列表`
- Example: `/furstar/artists/cn`
- URL: `furstar.jp/`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `NeverBehave`
- Source Location: `artists.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: 语言, 留空为jp, 支持cn, en


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
  - `furstar.jp/`
- `target`: `/artists`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/furstar/artists/cn",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "artists.ts",
  "maintainers": [
    "NeverBehave"
  ],
  "name": "画师列表",
  "parameters": {
    "lang": "语言, 留空为jp, 支持cn, en"
  },
  "path": "/artists/:lang?",
  "radar": [
    {
      "source": [
        "furstar.jp/"
      ],
      "target": "/artists"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Furstar 所有画家列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "113036045586930688",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://furstar.jp/",
      "title": "furstar 所有画家",
      "type": "feed",
      "url": "rsshub://furstar/artists/cn"
    },
    {
      "description": "Furstar 所有画家列表 - Powered by RSSHub",
      "errorAt": "2026-05-05T01:18:32.796Z",
      "errorMessage": "Failed to fetch\n",
      "id": "157430068202511360",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://furstar.jp/",
      "title": "furstar 所有画家",
      "type": "feed",
      "url": "rsshub://furstar/artists"
    }
  ],
  "url": "furstar.jp/"
}
```
