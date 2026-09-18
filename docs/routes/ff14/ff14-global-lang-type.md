# FINAL FANTASY XIV - FINAL FANTASY XIV (The Lodestone)

## Coverage
`index-only`

## Route
- Namespace: `ff14`
- Namespace Name: `FINAL FANTASY XIV`
- Route Path: `/ff14/global/:lang/:type?`
- Route Name: `FINAL FANTASY XIV (The Lodestone)`
- Example: `/ff14/global/na/all`
- URL: `eu.finalfantasyxiv.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `kmod-midori`
- Source Location: `ff14-global.ts`
- Source Module: `_None_`

## Description
Region

| North Ameria | Europe | France | Germany | Japan |
| ------------ | ------ | ------ | ------- | ----- |
| na           | eu     | fr     | de      | jp    |

Category

| all | topics | notices | maintenance | updates | status | developers |
| --- | ------ | ------- | ----------- | ------- | ------ | ---------- |

## Parameters
- `lang`: Region
- `type`: Category, `all` by default


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
  "description": "Region\n\n| North Ameria | Europe | France | Germany | Japan |\n| ------------ | ------ | ------ | ------- | ----- |\n| na           | eu     | fr     | de      | jp    |\n\nCategory\n\n| all | topics | notices | maintenance | updates | status | developers |\n| --- | ------ | ------- | ----------- | ------- | ------ | ---------- |",
  "example": "/ff14/global/na/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "ff14-global.ts",
  "maintainers": [
    "kmod-midori"
  ],
  "name": "FINAL FANTASY XIV (The Lodestone)",
  "parameters": {
    "lang": "Region",
    "type": "Category, `all` by default"
  },
  "path": "/global/:lang/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "FFXIV Lodestone updates (all) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81190222645790720",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://na.finalfantasyxiv.com/lodestone/news/",
      "title": "FFXIV Lodestone updates (all)",
      "type": "feed",
      "url": "rsshub://ff14/global/na/all"
    }
  ]
}
```
