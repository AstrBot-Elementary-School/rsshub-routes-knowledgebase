# IKEA - 中国 - 会员特惠

## Coverage
`index-only`

## Route
- Namespace: `ikea`
- Namespace Name: `IKEA`
- Route Path: `/ikea/cn/family_offers`
- Route Name: `中国 - 会员特惠`
- Example: `/ikea/cn/family_offers`
- URL: `ikea.cn/cn/zh/offers/family-offers`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `jzhangdev`
- Source Location: `cn/family-offers.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `ikea.cn/cn/zh/offers/family-offers`
  - `ikea.cn/`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/ikea/cn/family_offers",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cn/family-offers.ts",
  "maintainers": [
    "jzhangdev"
  ],
  "name": "中国 - 会员特惠",
  "parameters": {},
  "path": "/cn/family_offers",
  "radar": [
    {
      "source": [
        "ikea.cn/cn/zh/offers/family-offers",
        "ikea.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "ikea.cn/cn/zh/offers/family-offers"
}
```
