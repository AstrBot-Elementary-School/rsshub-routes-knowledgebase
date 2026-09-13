# BT 之家 1LOU 站 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `1lou`
- Namespace Name: `BT 之家 1LOU 站`
- Route Path: `/1lou/search/:params`
- Route Name: `搜索`
- Example: `/1lou/search/繁花`
- URL: `1lou.me/search`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `JimenezLi`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
搜索路由，支持关键词搜索。

## Parameters
- `params`: 搜索关键词


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `1lou.me/search`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "搜索路由，支持关键词搜索。",
  "example": "/1lou/search/繁花",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "search.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "搜索",
  "parameters": {
    "params": "搜索关键词"
  },
  "path": "/search/:params",
  "radar": [
    {
      "source": [
        "1lou.me/search"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "1lou.me/search"
}
```
