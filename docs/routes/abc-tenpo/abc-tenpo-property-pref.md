# ABC Tenpo - 新着物件

## Coverage
`index-only`

## Route
- Namespace: `abc-tenpo`
- Namespace Name: `ABC Tenpo`
- Route Path: `/abc-tenpo/property/:pref?`
- Route Name: `新着物件`
- Example: `/abc-tenpo/property/tokyo`
- URL: `www.abc-tenpo.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `property.ts`
- Source Module: `_None_`

## Description
Listings on ABC 店舗 sorted by 新着順 (first page, 20 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，階，最寄駅，引渡状態，現業態，業種制限，飲食条件，情報更新日，…) parsed from the list and detail pages; unknown values are `null`. 保証金，礼金 and 造作譲渡料 are members-only on the site and therefore always `null`; the item date is the site's 情報更新日.

| Query   | Description                                                                  | Default |
| ------- | ---------------------------------------------------------------------------- | ------- |
| `limit` | Number of listings to process (detail pages are fetched per listing), max 20 | 20      |

## Parameters
- `pref`: {"description": "Prefecture slug or JIS X 0401 code; omit for all of 東京・神奈川・千葉・埼玉", "options": [{"label": "東京都 (13)", "value": "tokyo"}, {"label": "神奈川県 (14)", "value": "kanagawa"}, {"label": "埼玉県 (11)", "value": "saitama"}, {"label": "千葉県 (12)", "value": "chiba"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.abc-tenpo.com/property/search`
  - `www.abc-tenpo.com/feature/new_arrival`
  - `www.abc-tenpo.com/`
- `target`: `/property`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Listings on ABC 店舗 sorted by 新着順 (first page, 20 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，階，最寄駅，引渡状態，現業態，業種制限，飲食条件，情報更新日，…) parsed from the list and detail pages; unknown values are `null`. 保証金，礼金 and 造作譲渡料 are members-only on the site and therefore always `null`; the item date is the site's 情報更新日.\n\n| Query   | Description                                                                  | Default |\n| ------- | ---------------------------------------------------------------------------- | ------- |\n| `limit` | Number of listings to process (detail pages are fetched per listing), max 20 | 20      |",
  "example": "/abc-tenpo/property/tokyo",
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
    "pref": {
      "description": "Prefecture slug or JIS X 0401 code; omit for all of 東京・神奈川・千葉・埼玉",
      "options": [
        {
          "label": "東京都 (13)",
          "value": "tokyo"
        },
        {
          "label": "神奈川県 (14)",
          "value": "kanagawa"
        },
        {
          "label": "埼玉県 (11)",
          "value": "saitama"
        },
        {
          "label": "千葉県 (12)",
          "value": "chiba"
        }
      ]
    }
  },
  "path": "/property/:pref?",
  "radar": [
    {
      "source": [
        "www.abc-tenpo.com/property/search",
        "www.abc-tenpo.com/feature/new_arrival",
        "www.abc-tenpo.com/"
      ],
      "target": "/property"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.abc-tenpo.com"
}
```
