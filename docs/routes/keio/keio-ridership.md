# Keio Corporation - 駅別 一日平均乗降人員

## Coverage
`index-only`

## Route
- Namespace: `keio`
- Namespace Name: `Keio Corporation`
- Route Path: `/keio/ridership`
- Route Name: `駅別 一日平均乗降人員`
- Example: `/keio/ridership`
- URL: `www.keio.co.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `ridership.ts`
- Source Module: `_None_`

## Description
Annual 駅別 一日平均乗降人員 for every Keio station (京王線 incl. 相模原線・高尾線 etc., and 井の頭線), from [駅別 一日平均乗降人員](https://www.keio.co.jp/company/corporate/corporate_manual/number-of-passengers.html). The page lists the latest fiscal year and the one before it side by side, so there is one item per station and year (two per station); there is no year parameter. `_extra` carries `operator`, `station`, `line`, `fiscal_year`, `daily_average` (人/日) and both cells in `raw`. `rank` is `null` (no ranking is printed); `yoy_pct` is computed from the two year columns for the latest year (rounded to 0.1) and `null` for the earlier one. 明大前's （乗換） transfer count is kept in `raw.note`; the 全線計 row is not a station and is skipped. The operator does not publish a release date, so items have no `pubDate`.

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
  - `www.keio.co.jp/company/corporate/corporate_manual/number-of-passengers.html`
- `target`: `/ridership`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Annual 駅別 一日平均乗降人員 for every Keio station (京王線 incl. 相模原線・高尾線 etc., and 井の頭線), from [駅別 一日平均乗降人員](https://www.keio.co.jp/company/corporate/corporate_manual/number-of-passengers.html). The page lists the latest fiscal year and the one before it side by side, so there is one item per station and year (two per station); there is no year parameter. `_extra` carries `operator`, `station`, `line`, `fiscal_year`, `daily_average` (人/日) and both cells in `raw`. `rank` is `null` (no ranking is printed); `yoy_pct` is computed from the two year columns for the latest year (rounded to 0.1) and `null` for the earlier one. 明大前's （乗換） transfer count is kept in `raw.note`; the 全線計 row is not a station and is skipped. The operator does not publish a release date, so items have no `pubDate`.",
  "example": "/keio/ridership",
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
  "name": "駅別 一日平均乗降人員",
  "parameters": {},
  "path": "/ridership",
  "radar": [
    {
      "source": [
        "www.keio.co.jp/company/corporate/corporate_manual/number-of-passengers.html"
      ],
      "target": "/ridership"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.keio.co.jp"
}
```
