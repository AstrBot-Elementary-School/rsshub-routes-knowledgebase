# Sonomama - 新着物件

## Coverage
`index-only`

## Route
- Namespace: `sonomama`
- Namespace Name: `Sonomama`
- Route Path: `/sonomama/property/:pref?`
- Route Name: `新着物件`
- Example: `/sonomama/property/tokyo`
- URL: `www.sonomama.net`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `property.ts`
- Source Module: `_None_`

## Description
New listings on 店舗そのままオークション，newest first (first page, 20 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，階，最寄駅，敷金・保証金，造作価格，業態，業種制限，…) parsed from the list and detail pages; unknown values are `null`. The site does not publish listing dates, so items have no `pubDate`.

| Query   | Description                                                                  | Default |
| ------- | ---------------------------------------------------------------------------- | ------- |
| `limit` | Number of listings to process (detail pages are fetched per listing), max 20 | 20      |

## Parameters
- `pref`: Prefecture slug (tokyo, kanagawa, saitama, chiba, osaka, kyoto, hyogo, aichi, fukuoka) or JIS X 0401 code; omit for nationwide


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.sonomama.net/app/`
  - `www.sonomama.net/`
- `target`: `/property`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "New listings on 店舗そのままオークション，newest first (first page, 20 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，階，最寄駅，敷金・保証金，造作価格，業態，業種制限，…) parsed from the list and detail pages; unknown values are `null`. The site does not publish listing dates, so items have no `pubDate`.\n\n| Query   | Description                                                                  | Default |\n| ------- | ---------------------------------------------------------------------------- | ------- |\n| `limit` | Number of listings to process (detail pages are fetched per listing), max 20 | 20      |",
  "example": "/sonomama/property/tokyo",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "property.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "新着物件",
  "parameters": {
    "pref": "Prefecture slug (tokyo, kanagawa, saitama, chiba, osaka, kyoto, hyogo, aichi, fukuoka) or JIS X 0401 code; omit for nationwide"
  },
  "path": "/property/:pref?",
  "radar": [
    {
      "source": [
        "www.sonomama.net/app/",
        "www.sonomama.net/"
      ],
      "target": "/property"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.sonomama.net"
}
```
