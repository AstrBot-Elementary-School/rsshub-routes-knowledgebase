# Odakyu Electric Railway - 駅別乗降人員

## Coverage
`index-only`

## Route
- Namespace: `odakyu`
- Namespace Name: `Odakyu Electric Railway`
- Route Path: `/odakyu/ridership`
- Route Name: `駅別乗降人員`
- Example: `/odakyu/ridership`
- URL: `www.odakyu.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `ridership.ts`
- Source Module: `_None_`

## Description
Annual 1日平均駅別乗降人員 for every Odakyu station (小田原線 / 江ノ島線 / 多摩線), from [鉄道部門：駅別乗降人員・輸送人員ほか](https://www.odakyu.jp/company/railroad/users/). The operator publishes only the current fiscal year on this page, so there is no year parameter. One item per station; `_extra` carries `operator`, `station`, `line`, `fiscal_year`, `daily_average` (人/日), `rank` (順位 across all lines), `yoy_pct` (増減率) and the page's cell text in `raw`. The operator does not publish a release date, so items have no `pubDate`.

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.odakyu.jp/company/railroad/users/`
- `target`: `/ridership`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Annual 1日平均駅別乗降人員 for every Odakyu station (小田原線 / 江ノ島線 / 多摩線), from [鉄道部門：駅別乗降人員・輸送人員ほか](https://www.odakyu.jp/company/railroad/users/). The operator publishes only the current fiscal year on this page, so there is no year parameter. One item per station; `_extra` carries `operator`, `station`, `line`, `fiscal_year`, `daily_average` (人/日), `rank` (順位 across all lines), `yoy_pct` (増減率) and the page's cell text in `raw`. The operator does not publish a release date, so items have no `pubDate`.",
  "example": "/odakyu/ridership",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "ridership.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "駅別乗降人員",
  "parameters": {},
  "path": "/ridership",
  "radar": [
    {
      "source": [
        "www.odakyu.jp/company/railroad/users/"
      ],
      "target": "/ridership"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.odakyu.jp"
}
```
