# Cointelegraph - News

## Coverage
`index-only`

## Route
- Namespace: `cointelegraph`
- Namespace Name: `Cointelegraph`
- Route Path: `/cointelegraph/`
- Route Name: `News`
- Example: `/cointelegraph`
- URL: `cointelegraph.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Get latest news from Cointelegraph with full text.

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
  - `cointelegraph.com/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Get latest news from Cointelegraph with full text.",
  "example": "/cointelegraph",
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
        "cointelegraph.com/"
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
