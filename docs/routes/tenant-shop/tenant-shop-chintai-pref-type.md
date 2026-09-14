# Tenant Shop Network - 新着物件

## Coverage
`index-only`

## Route
- Namespace: `tenant-shop`
- Namespace Name: `Tenant Shop Network`
- Route Path: `/tenant-shop/chintai/:pref?/:type?`
- Route Name: `新着物件`
- Example: `/tenant-shop/chintai/tokyo/food`
- URL: `www.tenant-shop.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `chintai.ts`
- Source Module: `_None_`

## Description
New listings (新着物件) on テナントショップネットワーク for one prefecture, newest first (first page, 30 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，保証金・敷金，礼金，物件登録日，…) parsed from the list and detail pages; unknown values are `null`. East Japan prefectures are served by tenant-shop.com and 愛知 and westward by tenant-shop.jp.

| Query   | Description                                                                  | Default |
| ------- | ---------------------------------------------------------------------------- | ------- |
| `limit` | Number of listings to process (detail pages are fetched per listing), max 30 | 30      |

## Parameters
- `pref`: {"default": "tokyo", "description": "Prefecture slug or the site's `pa` code", "options": [{"label": "東京都 (14)", "value": "tokyo"}, {"label": "神奈川県 (15)", "value": "kanagawa"}, {"label": "埼玉県 (16)", "value": "saitama"}, {"label": "千葉県 (17)", "value": "chiba"}, {"label": "茨城県 (18)", "value": "ibaraki"}, {"label": "栃木県 (19)", "value": "tochigi"}, {"label": "群馬県 (20)", "value": "gunma"}, {"label": "北海道 (7)", "value": "hokkaido"}, {"label": "宮城県 (10)", "value": "miyagi"}, {"label": "新潟県 (21)", "value": "niigata"}, {"label": "長野県 (28)", "value": "nagano"}, {"label": "愛知県 (25)", "value": "aichi"}, {"label": "岐阜県 (26)", "value": "gifu"}, {"label": "静岡県 (27)", "value": "shizuoka"}, {"label": "大阪府 (1)", "value": "osaka"}, {"label": "京都府 (31)", "value": "kyoto"}, {"label": "兵庫県 (32)", "value": "hyogo"}, {"label": "滋賀県 (5)", "value": "shiga"}, {"label": "奈良県 (34)", "value": "nara"}]}
- `type`: {"description": "Property type filter; omit for all types", "options": [{"label": "居抜き", "value": "inuki"}, {"label": "飲食", "value": "food"}, {"label": "オフィス", "value": "office"}, {"label": "物販・サービス", "value": "retail"}, {"label": "倉庫・工場", "value": "warehouse"}, {"label": "美容・エステ・医療", "value": "beauty"}, {"label": "沿道サービス・借地", "value": "roadside"}, {"label": "商業施設", "value": "mall"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-:pa/shin-1`
  - `www.tenant-shop.com/chintai_biz/pa-:pa`
- `target`: `/chintai/:pa`
### Rule 2
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-:pa/shin-1`
  - `www.tenant-shop.jp/chintai_biz/pa-:pa`
- `target`: `/chintai/:pa`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "New listings (新着物件) on テナントショップネットワーク for one prefecture, newest first (first page, 30 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，保証金・敷金，礼金，物件登録日，…) parsed from the list and detail pages; unknown values are `null`. East Japan prefectures are served by tenant-shop.com and 愛知 and westward by tenant-shop.jp.\n\n| Query   | Description                                                                  | Default |\n| ------- | ---------------------------------------------------------------------------- | ------- |\n| `limit` | Number of listings to process (detail pages are fetched per listing), max 30 | 30      |",
  "example": "/tenant-shop/chintai/tokyo/food",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "chintai.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "新着物件",
  "parameters": {
    "pref": {
      "default": "tokyo",
      "description": "Prefecture slug or the site's `pa` code",
      "options": [
        {
          "label": "東京都 (14)",
          "value": "tokyo"
        },
        {
          "label": "神奈川県 (15)",
          "value": "kanagawa"
        },
        {
          "label": "埼玉県 (16)",
          "value": "saitama"
        },
        {
          "label": "千葉県 (17)",
          "value": "chiba"
        },
        {
          "label": "茨城県 (18)",
          "value": "ibaraki"
        },
        {
          "label": "栃木県 (19)",
          "value": "tochigi"
        },
        {
          "label": "群馬県 (20)",
          "value": "gunma"
        },
        {
          "label": "北海道 (7)",
          "value": "hokkaido"
        },
        {
          "label": "宮城県 (10)",
          "value": "miyagi"
        },
        {
          "label": "新潟県 (21)",
          "value": "niigata"
        },
        {
          "label": "長野県 (28)",
          "value": "nagano"
        },
        {
          "label": "愛知県 (25)",
          "value": "aichi"
        },
        {
          "label": "岐阜県 (26)",
          "value": "gifu"
        },
        {
          "label": "静岡県 (27)",
          "value": "shizuoka"
        },
        {
          "label": "大阪府 (1)",
          "value": "osaka"
        },
        {
          "label": "京都府 (31)",
          "value": "kyoto"
        },
        {
          "label": "兵庫県 (32)",
          "value": "hyogo"
        },
        {
          "label": "滋賀県 (5)",
          "value": "shiga"
        },
        {
          "label": "奈良県 (34)",
          "value": "nara"
        }
      ]
    },
    "type": {
      "description": "Property type filter; omit for all types",
      "options": [
        {
          "label": "居抜き",
          "value": "inuki"
        },
        {
          "label": "飲食",
          "value": "food"
        },
        {
          "label": "オフィス",
          "value": "office"
        },
        {
          "label": "物販・サービス",
          "value": "retail"
        },
        {
          "label": "倉庫・工場",
          "value": "warehouse"
        },
        {
          "label": "美容・エステ・医療",
          "value": "beauty"
        },
        {
          "label": "沿道サービス・借地",
          "value": "roadside"
        },
        {
          "label": "商業施設",
          "value": "mall"
        }
      ]
    }
  },
  "path": "/chintai/:pref?/:type?",
  "radar": [
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-:pa/shin-1",
        "www.tenant-shop.com/chintai_biz/pa-:pa"
      ],
      "target": "/chintai/:pa"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-:pa/shin-1",
        "www.tenant-shop.jp/chintai_biz/pa-:pa"
      ],
      "target": "/chintai/:pa"
    }
  ],
  "topFeeds": [],
  "url": "www.tenant-shop.com"
}
```
