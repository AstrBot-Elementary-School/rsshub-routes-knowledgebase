# Syosetu - Novel Updates

## Coverage
`index-only`

## Route
- Namespace: `syosetu`
- Namespace Name: `Syosetu`
- Route Path: `/syosetu/:ncode`
- Route Name: `Novel Updates`
- Example: `/syosetu/n9292ii`
- URL: `syosetu.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `eternasuno, SnowAgar25`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `ncode`: Novel code, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `title`: `Novel Updates`
- `source`:
  - `ncode.syosetu.com/:ncode`
  - `ncode.syosetu.com/:ncode/:chapter`
- `target`: `/:ncode`
### Rule 2
- `title`: `Novel Updates`
- `source`:
  - `novel18.syosetu.com/:ncode`
  - `novel18.syosetu.com/:ncode/:chapter`
- `target`: `/:ncode`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/syosetu/n9292ii",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "eternasuno",
    "SnowAgar25"
  ],
  "name": "Novel Updates",
  "parameters": {
    "ncode": "Novel code, can be found in URL"
  },
  "path": "/:ncode",
  "radar": [
    {
      "source": [
        "ncode.syosetu.com/:ncode",
        "ncode.syosetu.com/:ncode/:chapter"
      ],
      "target": "/:ncode",
      "title": "Novel Updates"
    },
    {
      "source": [
        "novel18.syosetu.com/:ncode",
        "novel18.syosetu.com/:ncode/:chapter"
      ],
      "target": "/:ncode",
      "title": "Novel Updates"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
