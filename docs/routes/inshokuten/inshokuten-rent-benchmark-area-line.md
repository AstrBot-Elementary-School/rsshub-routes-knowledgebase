# Inshokuten.com - 賃料相場

## Coverage
`index-only`

## Route
- Namespace: `inshokuten`
- Namespace Name: `Inshokuten.com`
- Route Path: `/inshokuten/rent-benchmark/:area?/:line?`
- Route Name: `賃料相場`
- Example: `/inshokuten/rent-benchmark/23ward`
- URL: `www.inshokuten.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `rent-benchmark.ts`
- Source Module: `_None_`

## Description
Restaurant-property rent benchmarks (坪単価，消費税込み募集金額，直近 1 年間) published by 飲食店.COM. Without `line` the feed has one item per 市区町村 of the area; with `line` one item per station on that line. Each item's `_extra` carries `rent_per_tsubo_avg_jpy` / `_min_jpy` / `_max_jpy` (円 / 坪 / 月), `sample_count` (sum of the 賃料分布図 buckets), `period` and the raw site text; the site publishes no 中央値 and no 更新日，so `rent_per_tsubo_median_jpy` is always `null` and items carry no `pubDate`. Detail pages are cached for one day.

## Parameters
- `area`: {"default": "23ward", "description": "首都圏 sub-area", "options": [{"label": "東京23区", "value": "23ward"}, {"label": "東京都下", "value": "23ward_out"}, {"label": "千葉", "value": "chiba"}, {"label": "埼玉", "value": "saitama"}, {"label": "神奈川", "value": "yokohama_kawasaki"}]}
- `line`: {"description": "Line id from the area page (`/bukken/kanto/market/rent/line/{area}`, e.g. `2` = JR山手線 in 東京23区); when given, one item per station on that line instead of one per 市区町村"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.inshokuten.com/bukken/kanto/market/rent/line/:area`
- `target`: `/rent-benchmark/:area`
### Rule 2
- `source`:
  - `www.inshokuten.com/bukken/kanto/market/rent/station/:line`
- `target`: `/rent-benchmark/23ward/:line`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Restaurant-property rent benchmarks (坪単価，消費税込み募集金額，直近 1 年間) published by 飲食店.COM. Without `line` the feed has one item per 市区町村 of the area; with `line` one item per station on that line. Each item's `_extra` carries `rent_per_tsubo_avg_jpy` / `_min_jpy` / `_max_jpy` (円 / 坪 / 月), `sample_count` (sum of the 賃料分布図 buckets), `period` and the raw site text; the site publishes no 中央値 and no 更新日，so `rent_per_tsubo_median_jpy` is always `null` and items carry no `pubDate`. Detail pages are cached for one day.",
  "example": "/inshokuten/rent-benchmark/23ward",
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
  "name": "賃料相場",
  "parameters": {
    "area": {
      "default": "23ward",
      "description": "首都圏 sub-area",
      "options": [
        {
          "label": "東京23区",
          "value": "23ward"
        },
        {
          "label": "東京都下",
          "value": "23ward_out"
        },
        {
          "label": "千葉",
          "value": "chiba"
        },
        {
          "label": "埼玉",
          "value": "saitama"
        },
        {
          "label": "神奈川",
          "value": "yokohama_kawasaki"
        }
      ]
    },
    "line": {
      "description": "Line id from the area page (`/bukken/kanto/market/rent/line/{area}`, e.g. `2` = JR山手線 in 東京23区); when given, one item per station on that line instead of one per 市区町村"
    }
  },
  "path": "/rent-benchmark/:area?/:line?",
  "radar": [
    {
      "source": [
        "www.inshokuten.com/bukken/kanto/market/rent/line/:area"
      ],
      "target": "/rent-benchmark/:area"
    },
    {
      "source": [
        "www.inshokuten.com/bukken/kanto/market/rent/station/:line"
      ],
      "target": "/rent-benchmark/23ward/:line"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.inshokuten.com"
}
```
