# CryptoSlate - News

## Coverage
`index-only`

## Route
- Namespace: `cryptoslate`
- Namespace Name: `CryptoSlate`
- Route Path: `/cryptoslate/`
- Route Name: `News`
- Example: `/cryptoslate`
- URL: `cryptoslate.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Get latest news from CryptoSlate.

## Parameters
_None_


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
  - `cryptoslate.com/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Get latest news from CryptoSlate.",
  "example": "/cryptoslate",
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
    "pseudoyu"
  ],
  "name": "News",
  "parameters": {},
  "path": "/",
  "radar": [
    {
      "source": [
        "cryptoslate.com/"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
