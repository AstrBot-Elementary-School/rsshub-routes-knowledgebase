# Temposmart - 新着物件

## Coverage
`index-only`

## Route
- Namespace: `temposmart`
- Namespace Name: `Temposmart`
- Route Path: `/temposmart/estates/:pref?`
- Route Name: `新着物件`
- Example: `/temposmart/estates/tokyo`
- URL: `www.temposmart.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `estates.ts`
- Source Module: `_None_`

## Description
New listings on テンポスマート for one prefecture, sorted by 新着順 (first page, 50 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，保証金，礼金，造作譲渡料，現況，業種制限，登録日，…) parsed from the list and detail pages; unknown values are `null`.

| Query   | Description                                                                  | Default |
| ------- | ---------------------------------------------------------------------------- | ------- |
| `limit` | Number of listings to process (detail pages are fetched per listing), max 50 | 30      |

## Parameters
- `pref`: {"default": "tokyo", "description": "都道府県 slug or JIS X 0401 code", "options": [{"label": "東京都 (13)", "value": "tokyo"}, {"label": "神奈川県 (14)", "value": "kanagawa"}, {"label": "埼玉県 (11)", "value": "saitama"}, {"label": "千葉県 (12)", "value": "chiba"}, {"label": "大阪府 (27)", "value": "osaka"}, {"label": "京都府 (26)", "value": "kyoto"}, {"label": "兵庫県 (28)", "value": "hyogo"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.temposmart.jp/estates/pref/:pref`
- `target`: `/estates/:pref`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "New listings on テンポスマート for one prefecture, sorted by 新着順 (first page, 50 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，保証金，礼金，造作譲渡料，現況，業種制限，登録日，…) parsed from the list and detail pages; unknown values are `null`.\n\n| Query   | Description                                                                  | Default |\n| ------- | ---------------------------------------------------------------------------- | ------- |\n| `limit` | Number of listings to process (detail pages are fetched per listing), max 50 | 30      |",
  "example": "/temposmart/estates/tokyo",
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
    "pref": {
      "default": "tokyo",
      "description": "都道府県 slug or JIS X 0401 code",
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
        },
        {
          "label": "大阪府 (27)",
          "value": "osaka"
        },
        {
          "label": "京都府 (26)",
          "value": "kyoto"
        },
        {
          "label": "兵庫県 (28)",
          "value": "hyogo"
        }
      ]
    }
  },
  "path": "/estates/:pref?",
  "radar": [
    {
      "source": [
        "www.temposmart.jp/estates/pref/:pref"
      ],
      "target": "/estates/:pref"
    }
  ],
  "topFeeds": [],
  "url": "www.temposmart.jp"
}
```
