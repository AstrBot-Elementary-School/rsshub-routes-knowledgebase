# Japan Local Government - 東京都 飲食店営業許可 新規

## Coverage
`index-only`

## Route
- Namespace: `lg`
- Namespace Name: `Japan Local Government`
- Route Path: `/lg/tokyo/food-permit/:ward?`
- Route Name: `東京都 飲食店営業許可 新規`
- Example: `/lg/tokyo/food-permit`
- URL: `catalog.data.metro.tokyo.lg.jp`
- Language: `_None_`
- Categories: `government`
- Maintainers: `pseudoyu`
- Source Location: `tokyo/food-permit.ts`
- Source Module: `_None_`

## Description
Newly granted food business permits (飲食店営業許可 etc.) in Tokyo wards, from each ward's CC BY open data:

- 渋谷区: [食品営業許可施設一覧 (ArcGIS FeatureServer)](https://city-shibuya-data.opendata.arcgis.com/items/e68f41ebfa5f4ea490ca9af701d44e02) — current and previous month
- 港区: [食品営業許可一覧 (CSV)](https://catalog.data.metro.tokyo.lg.jp/dataset/t131032d0000000244) — monthly snapshot of valid permits, newest first
- 台東区: [食品衛生営業施設一覧](https://www.city.taito.lg.jp/kenkohukusi/kenkokikikanrieisei/food/syokuhin-sisetu/index.html) — the two newest monthly 新規許可 CSVs (updated on the 10th)
- 品川区: [食品衛生許可施設一覧](https://www.city.shinagawa.tokyo.jp/PC/kenkou/kenkou-eisei/kenkou-eisei-syokuhin/opendate.html) — the two newest monthly CSVs (updated on the 15th); individuals' names and addresses are masked by the publisher and come through as `null`
- 世田谷区: [食品関係施設情報の公開について](https://www.city.setagaya.lg.jp/02245/online_tetsuzuki/3246.html) — the two newest 例月新規許可施設一覧 CSVs (updated on the 15th)
- 目黒区: [飲食店等 (BODIK CKAN)](https://data.bodik.jp/dataset/131105_food_business) — the two newest 飲食店 新規 monthly CSVs (updated by the 10th)

Items are sorted by permit date (`pubDate`). `_extra` holds `source`, `ward`, `permit_no`, `name`, `address`, `town` (町字), `permit_date`, `first_permit_date`, `expires_at` (許可満了日), `closed_date` (廃業日 — non-null means the business has already closed), `business_type`, `lat` / `lon` and the publisher's original columns in `raw`. Every field a publisher omits is `null`, never `0` or an empty string. Only 許可 rows are included (届出 rows are skipped).

| Query   | Description                           | Default |
| ------- | ------------------------------------- | ------- |
| `limit` | Number of permits per source, max 500 | 100     |

## Parameters
- `ward`: {"description": "Ward; omit for all sources", "options": [{"label": "渋谷区", "value": "shibuya"}, {"label": "港区", "value": "minato"}, {"label": "台東区", "value": "taito"}, {"label": "品川区", "value": "shinagawa"}, {"label": "世田谷区", "value": "setagaya"}, {"label": "目黒区", "value": "meguro"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "Newly granted food business permits (飲食店営業許可 etc.) in Tokyo wards, from each ward's CC BY open data:\n\n- 渋谷区: [食品営業許可施設一覧 (ArcGIS FeatureServer)](https://city-shibuya-data.opendata.arcgis.com/items/e68f41ebfa5f4ea490ca9af701d44e02) — current and previous month\n- 港区: [食品営業許可一覧 (CSV)](https://catalog.data.metro.tokyo.lg.jp/dataset/t131032d0000000244) — monthly snapshot of valid permits, newest first\n- 台東区: [食品衛生営業施設一覧](https://www.city.taito.lg.jp/kenkohukusi/kenkokikikanrieisei/food/syokuhin-sisetu/index.html) — the two newest monthly 新規許可 CSVs (updated on the 10th)\n- 品川区: [食品衛生許可施設一覧](https://www.city.shinagawa.tokyo.jp/PC/kenkou/kenkou-eisei/kenkou-eisei-syokuhin/opendate.html) — the two newest monthly CSVs (updated on the 15th); individuals' names and addresses are masked by the publisher and come through as `null`\n- 世田谷区: [食品関係施設情報の公開について](https://www.city.setagaya.lg.jp/02245/online_tetsuzuki/3246.html) — the two newest 例月新規許可施設一覧 CSVs (updated on the 15th)\n- 目黒区: [飲食店等 (BODIK CKAN)](https://data.bodik.jp/dataset/131105_food_business) — the two newest 飲食店 新規 monthly CSVs (updated by the 10th)\n\nItems are sorted by permit date (`pubDate`). `_extra` holds `source`, `ward`, `permit_no`, `name`, `address`, `town` (町字), `permit_date`, `first_permit_date`, `expires_at` (許可満了日), `closed_date` (廃業日 — non-null means the business has already closed), `business_type`, `lat` / `lon` and the publisher's original columns in `raw`. Every field a publisher omits is `null`, never `0` or an empty string. Only 許可 rows are included (届出 rows are skipped).\n\n| Query   | Description                           | Default |\n| ------- | ------------------------------------- | ------- |\n| `limit` | Number of permits per source, max 500 | 100     |",
  "example": "/lg/tokyo/food-permit",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": false
  },
  "heat": 0,
  "location": "tokyo/food-permit.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "東京都 飲食店営業許可 新規",
  "parameters": {
    "ward": {
      "description": "Ward; omit for all sources",
      "options": [
        {
          "label": "渋谷区",
          "value": "shibuya"
        },
        {
          "label": "港区",
          "value": "minato"
        },
        {
          "label": "台東区",
          "value": "taito"
        },
        {
          "label": "品川区",
          "value": "shinagawa"
        },
        {
          "label": "世田谷区",
          "value": "setagaya"
        },
        {
          "label": "目黒区",
          "value": "meguro"
        }
      ]
    }
  },
  "path": "/tokyo/food-permit/:ward?",
  "topFeeds": [],
  "url": "catalog.data.metro.tokyo.lg.jp"
}
```
