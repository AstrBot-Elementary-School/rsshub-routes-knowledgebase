# ABC Tenpo - エリア別賃料相場

## Coverage
`index-only`

## Route
- Namespace: `abc-tenpo`
- Namespace Name: `ABC Tenpo`
- Route Path: `/abc-tenpo/rent-benchmark/:pref?`
- Route Name: `エリア別賃料相場`
- Example: `/abc-tenpo/rent-benchmark/tokyo`
- URL: `www.abc-tenpo.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `rent-benchmark.ts`
- Source Module: `_None_`

## Description
Ward-level restaurant-property rent benchmarks (坪単価) from ABC 店舗's エリア別の賃料相場 page, one item per 区 of 東京 23 区. The page gives a single unqualified 相場 figure per ward (「賃料相場は坪単価」, compiled from the site's own listings) — it is stored in `_extra.rent_per_tsubo_jpy` because the site does not say whether it is a mean or a median; 平均 / 中央値 / 最高 / 最低，sample count, period and 更新日 are not published and stay `null`. The page is cached for one day.

## Parameters
- `pref`: {"default": "tokyo", "description": "Prefecture slug; the site currently publishes 東京23区 only", "options": [{"label": "東京都", "value": "tokyo"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.abc-tenpo.com/feature/rent`
- `target`: `/rent-benchmark`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Ward-level restaurant-property rent benchmarks (坪単価) from ABC 店舗's エリア別の賃料相場 page, one item per 区 of 東京 23 区. The page gives a single unqualified 相場 figure per ward (「賃料相場は坪単価」, compiled from the site's own listings) — it is stored in `_extra.rent_per_tsubo_jpy` because the site does not say whether it is a mean or a median; 平均 / 中央値 / 最高 / 最低，sample count, period and 更新日 are not published and stay `null`. The page is cached for one day.",
  "example": "/abc-tenpo/rent-benchmark/tokyo",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "rent-benchmark.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "エリア別賃料相場",
  "parameters": {
    "pref": {
      "default": "tokyo",
      "description": "Prefecture slug; the site currently publishes 東京23区 only",
      "options": [
        {
          "label": "東京都",
          "value": "tokyo"
        }
      ]
    }
  },
  "path": "/rent-benchmark/:pref?",
  "radar": [
    {
      "source": [
        "www.abc-tenpo.com/feature/rent"
      ],
      "target": "/rent-benchmark"
    }
  ],
  "topFeeds": [],
  "url": "www.abc-tenpo.com"
}
```
