# Tianjin University 天津大学 - The Office of Academic Affairs

## Coverage
`index-only`

## Route
- Namespace: `tju`
- Namespace Name: `Tianjin University 天津大学`
- Route Path: `/tju/oaa/:type?`
- Route Name: `The Office of Academic Affairs`
- Example: `/tju/oaa/news`
- URL: `cic.tju.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `AlanZeng423, AmosChenYQ, SuperPung`
- Source Location: `oaa/index.ts`
- Source Module: `_None_`

## Description
| News | Notification |
| :--: | :----------: |
| news | notification |

## Parameters
- `type`: default `news`


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
    "university"
  ],
  "description": "| News | Notification |\n| :--: | :----------: |\n| news | notification |",
  "example": "/tju/oaa/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "oaa/index.ts",
  "maintainers": [
    "AlanZeng423",
    "AmosChenYQ",
    "SuperPung"
  ],
  "name": "The Office of Academic Affairs",
  "parameters": {
    "type": "default `news`"
  },
  "path": "/oaa/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
