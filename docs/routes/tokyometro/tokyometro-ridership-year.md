# Tokyo Metro - 各駅の乗降人員ランキング

## Coverage
`index-only`

## Route
- Namespace: `tokyometro`
- Namespace Name: `Tokyo Metro`
- Route Path: `/tokyometro/ridership/:year?`
- Route Name: `各駅の乗降人員ランキング`
- Example: `/tokyometro/ridership`
- URL: `www.tokyometro.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `ridership.ts`
- Source Module: `_None_`

## Description
Annual 駅別乗降人員 (one-day average) for every Tokyo Metro station, from [各駅の乗降人員ランキング](https://www.tokyometro.jp/corporate/enterprise/passenger_rail/transportation/passengers/index.html). One item per station and fiscal year; `_extra` carries `operator`, `station`, `line` (several lines joined with `・`), `fiscal_year`, `daily_average` (人/日), `rank`, `yoy_pct` and the page's cell text in `raw`. Stations in the 直通連絡駅・共用駅 table (渋谷, 北千住, 中目黒, …) have no rank because the operator does not rank them. 国会議事堂前 and 溜池山王 are listed as one station (国会・溜池), as on the page. The operator does not publish a release date, so items have no `pubDate`.

## Parameters
- `year`: {"description": "Fiscal year (`2020` … latest); omit for the latest year"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.tokyometro.jp/corporate/enterprise/passenger_rail/transportation/passengers/:page`
- `target`: `/ridership`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Annual 駅別乗降人員 (one-day average) for every Tokyo Metro station, from [各駅の乗降人員ランキング](https://www.tokyometro.jp/corporate/enterprise/passenger_rail/transportation/passengers/index.html). One item per station and fiscal year; `_extra` carries `operator`, `station`, `line` (several lines joined with `・`), `fiscal_year`, `daily_average` (人/日), `rank`, `yoy_pct` and the page's cell text in `raw`. Stations in the 直通連絡駅・共用駅 table (渋谷, 北千住, 中目黒, …) have no rank because the operator does not rank them. 国会議事堂前 and 溜池山王 are listed as one station (国会・溜池), as on the page. The operator does not publish a release date, so items have no `pubDate`.",
  "example": "/tokyometro/ridership",
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
  "name": "各駅の乗降人員ランキング",
  "parameters": {
    "year": {
      "description": "Fiscal year (`2020` … latest); omit for the latest year"
    }
  },
  "path": "/ridership/:year?",
  "radar": [
    {
      "source": [
        "www.tokyometro.jp/corporate/enterprise/passenger_rail/transportation/passengers/:page"
      ],
      "target": "/ridership"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.tokyometro.jp"
}
```
