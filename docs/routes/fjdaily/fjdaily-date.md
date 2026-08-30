# 福建日报 - 电子报

## Coverage
`index-only`

## Route
- Namespace: `fjdaily`
- Namespace Name: `福建日报`
- Route Path: `/fjdaily/:date?`
- Route Name: `电子报`
- Example: `/fjdaily/20260316`
- URL: `fjdaily.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `DakoWang`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
留空时抓取最新一期全部版面，也可以通过日期参数抓取指定日期的全部版面内容。

## Parameters
- `date`: 日期，格式为 `YYYYMMDD`，留空时抓取当天全部版面，例如 `20260316`


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
  - `fjrb.fjdaily.com/pc/col/index.html`
- `target`: `/`
### Rule 2
- `source`:
  - `fjrb.fjdaily.com/pc/col/:yearmonth/:day/node_:id.html`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "留空时抓取最新一期全部版面，也可以通过日期参数抓取指定日期的全部版面内容。",
  "example": "/fjdaily/20260316",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "DakoWang"
  ],
  "name": "电子报",
  "parameters": {
    "date": "日期，格式为 `YYYYMMDD`，留空时抓取当天全部版面，例如 `20260316`"
  },
  "path": "/:date?",
  "radar": [
    {
      "source": [
        "fjrb.fjdaily.com/pc/col/index.html"
      ],
      "target": "/"
    },
    {
      "source": [
        "fjrb.fjdaily.com/pc/col/:yearmonth/:day/node_:id.html"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
