# Temponw - 新着物件

## Coverage
`index-only`

## Route
- Namespace: `temponw`
- Namespace Name: `Temponw`
- Route Path: `/temponw/estates/:area?`
- Route Name: `新着物件`
- Example: `/temponw/estates/tokyo`
- URL: `www.temponw.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `estates.ts`
- Source Module: `_None_`

## Description
Listings on 店舗ネットワーク sorted by 新着順 (first two pages, 20 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，階，最寄駅，保証金，礼金，造作譲渡料，不可業態，…) parsed from the list and detail pages; unknown values are `null`. The site does not publish listing dates, so items have no `pubDate`; the same unit may be listed by several agencies under different ids.

## Parameters
- `area`: {"description": "`tokyo` for the 23 wards of Tokyo; omit for nationwide", "options": [{"label": "東京23区", "value": "tokyo"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.temponw.com/result`
  - `www.temponw.com/`
- `target`: `/estates`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Listings on 店舗ネットワーク sorted by 新着順 (first two pages, 20 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，階，最寄駅，保証金，礼金，造作譲渡料，不可業態，…) parsed from the list and detail pages; unknown values are `null`. The site does not publish listing dates, so items have no `pubDate`; the same unit may be listed by several agencies under different ids.",
  "example": "/temponw/estates/tokyo",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "estates.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "新着物件",
  "parameters": {
    "area": {
      "description": "`tokyo` for the 23 wards of Tokyo; omit for nationwide",
      "options": [
        {
          "label": "東京23区",
          "value": "tokyo"
        }
      ]
    }
  },
  "path": "/estates/:area?",
  "radar": [
    {
      "source": [
        "www.temponw.com/result",
        "www.temponw.com/"
      ],
      "target": "/estates"
    }
  ],
  "topFeeds": [],
  "url": "www.temponw.com"
}
```
