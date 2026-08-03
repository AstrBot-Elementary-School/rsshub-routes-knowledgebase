# 中央气象台 - 全国气象预警

## Coverage
`index-only`

## Route
- Namespace: `nmc`
- Namespace Name: `中央气象台`
- Route Path: `/nmc/weatheralarm/:province?`
- Route Name: `全国气象预警`
- Example: `/nmc/weatheralarm/广东省`
- URL: `nmc.cn/publish/alarm.html`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `ylc395`
- Source Location: `weatheralarm.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `province`: 省份


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
  - `nmc.cn/publish/alarm.html`
  - `nmc.cn/`
- `target`: `/weatheralarm`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/nmc/weatheralarm/广东省",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 34,
  "location": "weatheralarm.ts",
  "maintainers": [
    "ylc395"
  ],
  "name": "全国气象预警",
  "parameters": {
    "province": "省份"
  },
  "path": "/weatheralarm/:province?",
  "radar": [
    {
      "source": [
        "nmc.cn/publish/alarm.html",
        "nmc.cn/"
      ],
      "target": "/weatheralarm"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "中央气象台全国气象预警 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81352281930323968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.nmc.cn/publish/alarm.html",
      "title": "中央气象台全国气象预警",
      "type": "feed",
      "url": "rsshub://nmc/weatheralarm/%E5%9B%9B%E5%B7%9D%E7%9C%81"
    },
    {
      "description": "中央气象台全国气象预警 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74808527566350336",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.nmc.cn/publish/alarm.html",
      "title": "中央气象台全国气象预警",
      "type": "feed",
      "url": "rsshub://nmc/weatheralarm/%E4%B8%8A%E6%B5%B7%E5%B8%82"
    }
  ],
  "url": "nmc.cn/publish/alarm.html"
}
```
