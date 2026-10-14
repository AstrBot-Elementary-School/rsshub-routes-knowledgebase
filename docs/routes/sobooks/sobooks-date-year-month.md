# SoBooks - 归档

## Coverage
`index-only`

## Route
- Namespace: `sobooks`
- Namespace Name: `SoBooks`
- Route Path: `/sobooks/date/:year/:month`
- Route Name: `归档`
- Example: `/sobooks/date/2020/11`
- URL: `sobooks.cc`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `date-source.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `year`: 归档年份
- `month`: 归档月份


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
  - `sobooks.net/books/date/:year/:month`
- `target`: `/date/:year/:month`
### Rule 2
- `source`:
  - `sobooks.cc/books/date/:year/:month`
- `target`: `/date/:year/:month`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/sobooks/date/2020/11",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "date-source.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "归档",
  "parameters": {
    "month": "归档月份",
    "year": "归档年份"
  },
  "path": "/date/:year/:month",
  "radar": [
    {
      "source": [
        "sobooks.net/books/date/:year/:month"
      ],
      "target": "/date/:year/:month"
    },
    {
      "source": [
        "sobooks.cc/books/date/:year/:month"
      ],
      "target": "/date/:year/:month"
    }
  ],
  "topFeeds": []
}
```
