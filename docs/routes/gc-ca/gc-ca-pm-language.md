# Prime Minister of Canada - News

## Coverage
`index-only`

## Route
- Namespace: `gc.ca`
- Namespace Name: `Prime Minister of Canada`
- Route Path: `/gc.ca/pm/:language?`
- Route Name: `News`
- Example: `/gc.ca/pm/en`
- URL: `pm.gc.ca`
- Language: `_None_`
- Categories: `government`
- Maintainers: `elibroftw`
- Source Location: `pm-news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `language`: Language (en or fr)


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
  - `pm.gc.ca`
  - `pm.gc.ca/:language`
  - `pm.gc.ca/:language/news`
  - `pm.gc.ca/:language/nouvelles`
- `target`: `/pm/:language`
### Rule 2
- `source`:
  - `pm.gc.ca`
- `target`: `/pm`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gc.ca/pm/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "pm-news.ts",
  "maintainers": [
    "elibroftw"
  ],
  "name": "News",
  "parameters": {
    "language": "Language (en or fr)"
  },
  "path": "/pm/:language?",
  "radar": [
    {
      "source": [
        "pm.gc.ca",
        "pm.gc.ca/:language",
        "pm.gc.ca/:language/news",
        "pm.gc.ca/:language/nouvelles"
      ],
      "target": "/pm/:language"
    },
    {
      "source": [
        "pm.gc.ca"
      ],
      "target": "/pm"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
