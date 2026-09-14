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

Items are sorted by permit date (`pubDate`). `_extra` holds `source`, `ward`, `permit_no`, `name`, `address`, `permit_date`, `business_type` and the publisher's original columns in `raw`. Only 許可 rows are included (届出 rows are skipped).

| Query   | Description                           | Default |
| ------- | ------------------------------------- | ------- |
| `limit` | Number of permits per source, max 500 | 100     |

## Parameters
- `ward`: {"description": "Ward; omit for all sources", "options": [{"label": "渋谷区", "value": "shibuya"}, {"label": "港区", "value": "minato"}]}


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
  "description": "Newly granted food business permits (飲食店営業許可 etc.) in Tokyo wards, from each ward's CC BY open data:\n\n- 渋谷区: [食品営業許可施設一覧 (ArcGIS FeatureServer)](https://city-shibuya-data.opendata.arcgis.com/items/e68f41ebfa5f4ea490ca9af701d44e02) — current and previous month\n- 港区: [食品営業許可一覧 (CSV)](https://catalog.data.metro.tokyo.lg.jp/dataset/t131032d0000000244) — monthly snapshot of valid permits, newest first\n\nItems are sorted by permit date (`pubDate`). `_extra` holds `source`, `ward`, `permit_no`, `name`, `address`, `permit_date`, `business_type` and the publisher's original columns in `raw`. Only 許可 rows are included (届出 rows are skipped).\n\n| Query   | Description                           | Default |\n| ------- | ------------------------------------- | ------- |\n| `limit` | Number of permits per source, max 500 | 100     |",
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
        }
      ]
    }
  },
  "path": "/tokyo/food-permit/:ward?",
  "topFeeds": [],
  "url": "catalog.data.metro.tokyo.lg.jp"
}
```
