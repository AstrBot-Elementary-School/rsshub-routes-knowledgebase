# Taiwan News - Hot News

## Coverage
`index-only`

## Route
- Namespace: `taiwannews`
- Namespace Name: `Taiwan News`
- Route Path: `/taiwannews/hot/:lang?`
- Route Name: `Hot News`
- Example: `/taiwannews/hot`
- URL: `taiwannews.com.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `hot.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: Language, `en` or `zh`, `en` by default


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
  - `taiwannews.com.tw/:lang/index`
- `target`: `/hot/:lang`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/taiwannews/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "hot.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Hot News",
  "parameters": {
    "lang": "Language, `en` or `zh`, `en` by default"
  },
  "path": "/hot/:lang?",
  "radar": [
    {
      "source": [
        "taiwannews.com.tw/:lang/index"
      ],
      "target": "/hot/:lang"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
