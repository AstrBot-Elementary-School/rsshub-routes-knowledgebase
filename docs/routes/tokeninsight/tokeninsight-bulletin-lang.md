# TokenInsight - Latest

## Coverage
`index-only`

## Route
- Namespace: `tokeninsight`
- Namespace Name: `TokenInsight`
- Route Path: `/tokeninsight/bulletin/:lang?`
- Route Name: `Latest`
- Example: `/tokeninsight/bulletin/en`
- URL: `tokeninsight.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `fuergaosi233`
- Source Location: `bulletin.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: Language, see below, Chinese by default


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
  - `tokeninsight.com/:lang/latest`
- `target`: `/bulletin/:lang`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/tokeninsight/bulletin/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "bulletin.ts",
  "maintainers": [
    "fuergaosi233"
  ],
  "name": "Latest",
  "parameters": {
    "lang": "Language, see below, Chinese by default"
  },
  "path": "/bulletin/:lang?",
  "radar": [
    {
      "source": [
        "tokeninsight.com/:lang/latest"
      ],
      "target": "/bulletin/:lang"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
