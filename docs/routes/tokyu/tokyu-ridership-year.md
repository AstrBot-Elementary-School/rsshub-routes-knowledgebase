# Tokyu Railways - 駅別乗降人員

## Coverage
`index-only`

## Route
- Namespace: `tokyu`
- Namespace Name: `Tokyu Railways`
- Route Path: `/tokyu/ridership/:year?`
- Route Name: `駅別乗降人員`
- Example: `/tokyu/ridership`
- URL: `www.tokyu.co.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `ridership.ts`
- Source Module: `_None_`

## Description
Annual 駅別乗降人員 (one-day average) for every Tokyu station, from [駅別乗降人員・輸送人員](https://www.tokyu.co.jp/railway/company/business/passengers/). One item per station, line and fiscal year (渋谷, 日吉, 蒲田 … appear once per line, as on the page); `_extra` carries `operator`, `station`, `line`, `fiscal_year`, `daily_average` (計, 人/日), `yoy_pct` and the page's cell text in `raw` (定期 / 定期外 / 計 / 前年比 / previous-year figure). `rank` is `null` because the operator publishes no ranking. 世田谷線 is published as a single 全線 figure and is not included. The operator does not publish a release date, so items have no `pubDate`.

## Parameters
- `year`: {"description": "Fiscal year (`2014` … latest); omit for the latest year"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.tokyu.co.jp/railway/company/business/passengers/:year`
  - `www.tokyu.co.jp/railway/company/business/passengers/`
- `target`: `/ridership/:year`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Annual 駅別乗降人員 (one-day average) for every Tokyu station, from [駅別乗降人員・輸送人員](https://www.tokyu.co.jp/railway/company/business/passengers/). One item per station, line and fiscal year (渋谷, 日吉, 蒲田 … appear once per line, as on the page); `_extra` carries `operator`, `station`, `line`, `fiscal_year`, `daily_average` (計, 人/日), `yoy_pct` and the page's cell text in `raw` (定期 / 定期外 / 計 / 前年比 / previous-year figure). `rank` is `null` because the operator publishes no ranking. 世田谷線 is published as a single 全線 figure and is not included. The operator does not publish a release date, so items have no `pubDate`.",
  "example": "/tokyu/ridership",
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
  "parameters": {
    "year": {
      "description": "Fiscal year (`2014` … latest); omit for the latest year"
    }
  },
  "path": "/ridership/:year?",
  "radar": [
    {
      "source": [
        "www.tokyu.co.jp/railway/company/business/passengers/:year",
        "www.tokyu.co.jp/railway/company/business/passengers/"
      ],
      "target": "/ridership/:year"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.tokyu.co.jp"
}
```
