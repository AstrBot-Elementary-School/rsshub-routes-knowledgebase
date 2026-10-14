# 机核网 - 预告

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/gcores/radios/preview`
- Route Name: `预告`
- Example: `/gcores/radios/preview`
- URL: `www.gcores.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `program-previews.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.gcores.com/radios/preview`
- `target`: `/radios/preview`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/gcores/radios/preview",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "program-previews.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "预告",
  "path": "/radios/preview",
  "radar": [
    {
      "source": [
        "www.gcores.com/radios/preview"
      ],
      "target": "/radios/preview"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "www.gcores.com",
  "view": 5
}
```
