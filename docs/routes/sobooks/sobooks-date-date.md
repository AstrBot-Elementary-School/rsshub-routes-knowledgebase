# SoBooks - 归档

## Coverage
`index-only`

## Route
- Namespace: `sobooks`
- Namespace Name: `SoBooks`
- Route Path: `/sobooks/date/:date?`
- Route Name: `归档`
- Example: `/sobooks/date/2020-11`
- URL: `sobooks.cc`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `date.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `date`: 日期，见例子，默认为当前年月


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
    "reading"
  ],
  "example": "/sobooks/date/2020-11",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "date.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "归档",
  "parameters": {
    "date": "日期，见例子，默认为当前年月"
  },
  "path": "/date/:date?",
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
