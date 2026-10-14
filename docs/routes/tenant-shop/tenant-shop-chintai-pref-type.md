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
  - `www.tenant-shop.com/chintai_biz/pa-14`
  - `www.tenant-shop.com/chintai_biz/pa-14/shin-1`
- `target`: `/chintai/tokyo`
### Rule 2
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-14/f1-1`
  - `www.tenant-shop.com/chintai_biz/pa-14/f1-1/shin-1`
- `target`: `/chintai/tokyo/inuki`
### Rule 3
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-14/f2-1`
  - `www.tenant-shop.com/chintai_biz/pa-14/f2-1/shin-1`
- `target`: `/chintai/tokyo/food`
### Rule 4
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-14/f3-1`
  - `www.tenant-shop.com/chintai_biz/pa-14/f3-1/shin-1`
- `target`: `/chintai/tokyo/office`
### Rule 5
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-14/f4-1`
  - `www.tenant-shop.com/chintai_biz/pa-14/f4-1/shin-1`
- `target`: `/chintai/tokyo/retail`
### Rule 6
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-14/f5-1`
  - `www.tenant-shop.com/chintai_biz/pa-14/f5-1/shin-1`
- `target`: `/chintai/tokyo/warehouse`
### Rule 7
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-14/f6-1`
  - `www.tenant-shop.com/chintai_biz/pa-14/f6-1/shin-1`
- `target`: `/chintai/tokyo/beauty`
### Rule 8
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-14/f7-1`
  - `www.tenant-shop.com/chintai_biz/pa-14/f7-1/shin-1`
- `target`: `/chintai/tokyo/roadside`
### Rule 9
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-14/f8-1`
  - `www.tenant-shop.com/chintai_biz/pa-14/f8-1/shin-1`
- `target`: `/chintai/tokyo/mall`
### Rule 10
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-15`
  - `www.tenant-shop.com/chintai_biz/pa-15/shin-1`
- `target`: `/chintai/kanagawa`
### Rule 11
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-15/f1-1`
  - `www.tenant-shop.com/chintai_biz/pa-15/f1-1/shin-1`
- `target`: `/chintai/kanagawa/inuki`
### Rule 12
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-15/f2-1`
  - `www.tenant-shop.com/chintai_biz/pa-15/f2-1/shin-1`
- `target`: `/chintai/kanagawa/food`
### Rule 13
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-15/f3-1`
  - `www.tenant-shop.com/chintai_biz/pa-15/f3-1/shin-1`
- `target`: `/chintai/kanagawa/office`
### Rule 14
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-15/f4-1`
  - `www.tenant-shop.com/chintai_biz/pa-15/f4-1/shin-1`
- `target`: `/chintai/kanagawa/retail`
### Rule 15
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-15/f5-1`
  - `www.tenant-shop.com/chintai_biz/pa-15/f5-1/shin-1`
- `target`: `/chintai/kanagawa/warehouse`
### Rule 16
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-15/f6-1`
  - `www.tenant-shop.com/chintai_biz/pa-15/f6-1/shin-1`
- `target`: `/chintai/kanagawa/beauty`
### Rule 17
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-15/f7-1`
  - `www.tenant-shop.com/chintai_biz/pa-15/f7-1/shin-1`
- `target`: `/chintai/kanagawa/roadside`
### Rule 18
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-15/f8-1`
  - `www.tenant-shop.com/chintai_biz/pa-15/f8-1/shin-1`
- `target`: `/chintai/kanagawa/mall`
### Rule 19
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-16`
  - `www.tenant-shop.com/chintai_biz/pa-16/shin-1`
- `target`: `/chintai/saitama`
### Rule 20
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-16/f1-1`
  - `www.tenant-shop.com/chintai_biz/pa-16/f1-1/shin-1`
- `target`: `/chintai/saitama/inuki`
### Rule 21
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-16/f2-1`
  - `www.tenant-shop.com/chintai_biz/pa-16/f2-1/shin-1`
- `target`: `/chintai/saitama/food`
### Rule 22
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-16/f3-1`
  - `www.tenant-shop.com/chintai_biz/pa-16/f3-1/shin-1`
- `target`: `/chintai/saitama/office`
### Rule 23
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-16/f4-1`
  - `www.tenant-shop.com/chintai_biz/pa-16/f4-1/shin-1`
- `target`: `/chintai/saitama/retail`
### Rule 24
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-16/f5-1`
  - `www.tenant-shop.com/chintai_biz/pa-16/f5-1/shin-1`
- `target`: `/chintai/saitama/warehouse`
### Rule 25
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-16/f6-1`
  - `www.tenant-shop.com/chintai_biz/pa-16/f6-1/shin-1`
- `target`: `/chintai/saitama/beauty`
### Rule 26
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-16/f7-1`
  - `www.tenant-shop.com/chintai_biz/pa-16/f7-1/shin-1`
- `target`: `/chintai/saitama/roadside`
### Rule 27
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-16/f8-1`
  - `www.tenant-shop.com/chintai_biz/pa-16/f8-1/shin-1`
- `target`: `/chintai/saitama/mall`
### Rule 28
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-17`
  - `www.tenant-shop.com/chintai_biz/pa-17/shin-1`
- `target`: `/chintai/chiba`
### Rule 29
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-17/f1-1`
  - `www.tenant-shop.com/chintai_biz/pa-17/f1-1/shin-1`
- `target`: `/chintai/chiba/inuki`
### Rule 30
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-17/f2-1`
  - `www.tenant-shop.com/chintai_biz/pa-17/f2-1/shin-1`
- `target`: `/chintai/chiba/food`
### Rule 31
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-17/f3-1`
  - `www.tenant-shop.com/chintai_biz/pa-17/f3-1/shin-1`
- `target`: `/chintai/chiba/office`
### Rule 32
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-17/f4-1`
  - `www.tenant-shop.com/chintai_biz/pa-17/f4-1/shin-1`
- `target`: `/chintai/chiba/retail`
### Rule 33
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-17/f5-1`
  - `www.tenant-shop.com/chintai_biz/pa-17/f5-1/shin-1`
- `target`: `/chintai/chiba/warehouse`
### Rule 34
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-17/f6-1`
  - `www.tenant-shop.com/chintai_biz/pa-17/f6-1/shin-1`
- `target`: `/chintai/chiba/beauty`
### Rule 35
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-17/f7-1`
  - `www.tenant-shop.com/chintai_biz/pa-17/f7-1/shin-1`
- `target`: `/chintai/chiba/roadside`
### Rule 36
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-17/f8-1`
  - `www.tenant-shop.com/chintai_biz/pa-17/f8-1/shin-1`
- `target`: `/chintai/chiba/mall`
### Rule 37
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-18`
  - `www.tenant-shop.com/chintai_biz/pa-18/shin-1`
- `target`: `/chintai/ibaraki`
### Rule 38
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-18/f1-1`
  - `www.tenant-shop.com/chintai_biz/pa-18/f1-1/shin-1`
- `target`: `/chintai/ibaraki/inuki`
### Rule 39
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-18/f2-1`
  - `www.tenant-shop.com/chintai_biz/pa-18/f2-1/shin-1`
- `target`: `/chintai/ibaraki/food`
### Rule 40
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-18/f3-1`
  - `www.tenant-shop.com/chintai_biz/pa-18/f3-1/shin-1`
- `target`: `/chintai/ibaraki/office`
### Rule 41
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-18/f4-1`
  - `www.tenant-shop.com/chintai_biz/pa-18/f4-1/shin-1`
- `target`: `/chintai/ibaraki/retail`
### Rule 42
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-18/f5-1`
  - `www.tenant-shop.com/chintai_biz/pa-18/f5-1/shin-1`
- `target`: `/chintai/ibaraki/warehouse`
### Rule 43
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-18/f6-1`
  - `www.tenant-shop.com/chintai_biz/pa-18/f6-1/shin-1`
- `target`: `/chintai/ibaraki/beauty`
### Rule 44
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-18/f7-1`
  - `www.tenant-shop.com/chintai_biz/pa-18/f7-1/shin-1`
- `target`: `/chintai/ibaraki/roadside`
### Rule 45
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-18/f8-1`
  - `www.tenant-shop.com/chintai_biz/pa-18/f8-1/shin-1`
- `target`: `/chintai/ibaraki/mall`
### Rule 46
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-19`
  - `www.tenant-shop.com/chintai_biz/pa-19/shin-1`
- `target`: `/chintai/tochigi`
### Rule 47
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-19/f1-1`
  - `www.tenant-shop.com/chintai_biz/pa-19/f1-1/shin-1`
- `target`: `/chintai/tochigi/inuki`
### Rule 48
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-19/f2-1`
  - `www.tenant-shop.com/chintai_biz/pa-19/f2-1/shin-1`
- `target`: `/chintai/tochigi/food`
### Rule 49
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-19/f3-1`
  - `www.tenant-shop.com/chintai_biz/pa-19/f3-1/shin-1`
- `target`: `/chintai/tochigi/office`
### Rule 50
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-19/f4-1`
  - `www.tenant-shop.com/chintai_biz/pa-19/f4-1/shin-1`
- `target`: `/chintai/tochigi/retail`
### Rule 51
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-19/f5-1`
  - `www.tenant-shop.com/chintai_biz/pa-19/f5-1/shin-1`
- `target`: `/chintai/tochigi/warehouse`
### Rule 52
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-19/f6-1`
  - `www.tenant-shop.com/chintai_biz/pa-19/f6-1/shin-1`
- `target`: `/chintai/tochigi/beauty`
### Rule 53
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-19/f7-1`
  - `www.tenant-shop.com/chintai_biz/pa-19/f7-1/shin-1`
- `target`: `/chintai/tochigi/roadside`
### Rule 54
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-19/f8-1`
  - `www.tenant-shop.com/chintai_biz/pa-19/f8-1/shin-1`
- `target`: `/chintai/tochigi/mall`
### Rule 55
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-20`
  - `www.tenant-shop.com/chintai_biz/pa-20/shin-1`
- `target`: `/chintai/gunma`
### Rule 56
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-20/f1-1`
  - `www.tenant-shop.com/chintai_biz/pa-20/f1-1/shin-1`
- `target`: `/chintai/gunma/inuki`
### Rule 57
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-20/f2-1`
  - `www.tenant-shop.com/chintai_biz/pa-20/f2-1/shin-1`
- `target`: `/chintai/gunma/food`
### Rule 58
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-20/f3-1`
  - `www.tenant-shop.com/chintai_biz/pa-20/f3-1/shin-1`
- `target`: `/chintai/gunma/office`
### Rule 59
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-20/f4-1`
  - `www.tenant-shop.com/chintai_biz/pa-20/f4-1/shin-1`
- `target`: `/chintai/gunma/retail`
### Rule 60
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-20/f5-1`
  - `www.tenant-shop.com/chintai_biz/pa-20/f5-1/shin-1`
- `target`: `/chintai/gunma/warehouse`
### Rule 61
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-20/f6-1`
  - `www.tenant-shop.com/chintai_biz/pa-20/f6-1/shin-1`
- `target`: `/chintai/gunma/beauty`
### Rule 62
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-20/f7-1`
  - `www.tenant-shop.com/chintai_biz/pa-20/f7-1/shin-1`
- `target`: `/chintai/gunma/roadside`
### Rule 63
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-20/f8-1`
  - `www.tenant-shop.com/chintai_biz/pa-20/f8-1/shin-1`
- `target`: `/chintai/gunma/mall`
### Rule 64
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-7`
  - `www.tenant-shop.com/chintai_biz/pa-7/shin-1`
- `target`: `/chintai/hokkaido`
### Rule 65
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-7/f1-1`
  - `www.tenant-shop.com/chintai_biz/pa-7/f1-1/shin-1`
- `target`: `/chintai/hokkaido/inuki`
### Rule 66
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-7/f2-1`
  - `www.tenant-shop.com/chintai_biz/pa-7/f2-1/shin-1`
- `target`: `/chintai/hokkaido/food`
### Rule 67
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-7/f3-1`
  - `www.tenant-shop.com/chintai_biz/pa-7/f3-1/shin-1`
- `target`: `/chintai/hokkaido/office`
### Rule 68
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-7/f4-1`
  - `www.tenant-shop.com/chintai_biz/pa-7/f4-1/shin-1`
- `target`: `/chintai/hokkaido/retail`
### Rule 69
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-7/f5-1`
  - `www.tenant-shop.com/chintai_biz/pa-7/f5-1/shin-1`
- `target`: `/chintai/hokkaido/warehouse`
### Rule 70
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-7/f6-1`
  - `www.tenant-shop.com/chintai_biz/pa-7/f6-1/shin-1`
- `target`: `/chintai/hokkaido/beauty`
### Rule 71
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-7/f7-1`
  - `www.tenant-shop.com/chintai_biz/pa-7/f7-1/shin-1`
- `target`: `/chintai/hokkaido/roadside`
### Rule 72
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-7/f8-1`
  - `www.tenant-shop.com/chintai_biz/pa-7/f8-1/shin-1`
- `target`: `/chintai/hokkaido/mall`
### Rule 73
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-10`
  - `www.tenant-shop.com/chintai_biz/pa-10/shin-1`
- `target`: `/chintai/miyagi`
### Rule 74
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-10/f1-1`
  - `www.tenant-shop.com/chintai_biz/pa-10/f1-1/shin-1`
- `target`: `/chintai/miyagi/inuki`
### Rule 75
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-10/f2-1`
  - `www.tenant-shop.com/chintai_biz/pa-10/f2-1/shin-1`
- `target`: `/chintai/miyagi/food`
### Rule 76
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-10/f3-1`
  - `www.tenant-shop.com/chintai_biz/pa-10/f3-1/shin-1`
- `target`: `/chintai/miyagi/office`
### Rule 77
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-10/f4-1`
  - `www.tenant-shop.com/chintai_biz/pa-10/f4-1/shin-1`
- `target`: `/chintai/miyagi/retail`
### Rule 78
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-10/f5-1`
  - `www.tenant-shop.com/chintai_biz/pa-10/f5-1/shin-1`
- `target`: `/chintai/miyagi/warehouse`
### Rule 79
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-10/f6-1`
  - `www.tenant-shop.com/chintai_biz/pa-10/f6-1/shin-1`
- `target`: `/chintai/miyagi/beauty`
### Rule 80
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-10/f7-1`
  - `www.tenant-shop.com/chintai_biz/pa-10/f7-1/shin-1`
- `target`: `/chintai/miyagi/roadside`
### Rule 81
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-10/f8-1`
  - `www.tenant-shop.com/chintai_biz/pa-10/f8-1/shin-1`
- `target`: `/chintai/miyagi/mall`
### Rule 82
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-21`
  - `www.tenant-shop.com/chintai_biz/pa-21/shin-1`
- `target`: `/chintai/niigata`
### Rule 83
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-21/f1-1`
  - `www.tenant-shop.com/chintai_biz/pa-21/f1-1/shin-1`
- `target`: `/chintai/niigata/inuki`
### Rule 84
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-21/f2-1`
  - `www.tenant-shop.com/chintai_biz/pa-21/f2-1/shin-1`
- `target`: `/chintai/niigata/food`
### Rule 85
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-21/f3-1`
  - `www.tenant-shop.com/chintai_biz/pa-21/f3-1/shin-1`
- `target`: `/chintai/niigata/office`
### Rule 86
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-21/f4-1`
  - `www.tenant-shop.com/chintai_biz/pa-21/f4-1/shin-1`
- `target`: `/chintai/niigata/retail`
### Rule 87
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-21/f5-1`
  - `www.tenant-shop.com/chintai_biz/pa-21/f5-1/shin-1`
- `target`: `/chintai/niigata/warehouse`
### Rule 88
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-21/f6-1`
  - `www.tenant-shop.com/chintai_biz/pa-21/f6-1/shin-1`
- `target`: `/chintai/niigata/beauty`
### Rule 89
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-21/f7-1`
  - `www.tenant-shop.com/chintai_biz/pa-21/f7-1/shin-1`
- `target`: `/chintai/niigata/roadside`
### Rule 90
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-21/f8-1`
  - `www.tenant-shop.com/chintai_biz/pa-21/f8-1/shin-1`
- `target`: `/chintai/niigata/mall`
### Rule 91
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-28`
  - `www.tenant-shop.com/chintai_biz/pa-28/shin-1`
- `target`: `/chintai/nagano`
### Rule 92
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-28/f1-1`
  - `www.tenant-shop.com/chintai_biz/pa-28/f1-1/shin-1`
- `target`: `/chintai/nagano/inuki`
### Rule 93
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-28/f2-1`
  - `www.tenant-shop.com/chintai_biz/pa-28/f2-1/shin-1`
- `target`: `/chintai/nagano/food`
### Rule 94
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-28/f3-1`
  - `www.tenant-shop.com/chintai_biz/pa-28/f3-1/shin-1`
- `target`: `/chintai/nagano/office`
### Rule 95
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-28/f4-1`
  - `www.tenant-shop.com/chintai_biz/pa-28/f4-1/shin-1`
- `target`: `/chintai/nagano/retail`
### Rule 96
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-28/f5-1`
  - `www.tenant-shop.com/chintai_biz/pa-28/f5-1/shin-1`
- `target`: `/chintai/nagano/warehouse`
### Rule 97
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-28/f6-1`
  - `www.tenant-shop.com/chintai_biz/pa-28/f6-1/shin-1`
- `target`: `/chintai/nagano/beauty`
### Rule 98
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-28/f7-1`
  - `www.tenant-shop.com/chintai_biz/pa-28/f7-1/shin-1`
- `target`: `/chintai/nagano/roadside`
### Rule 99
- `source`:
  - `www.tenant-shop.com/chintai_biz/pa-28/f8-1`
  - `www.tenant-shop.com/chintai_biz/pa-28/f8-1/shin-1`
- `target`: `/chintai/nagano/mall`
### Rule 100
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-25`
  - `www.tenant-shop.jp/chintai_biz/pa-25/shin-1`
- `target`: `/chintai/aichi`
### Rule 101
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-25/f1-1`
  - `www.tenant-shop.jp/chintai_biz/pa-25/f1-1/shin-1`
- `target`: `/chintai/aichi/inuki`
### Rule 102
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-25/f2-1`
  - `www.tenant-shop.jp/chintai_biz/pa-25/f2-1/shin-1`
- `target`: `/chintai/aichi/food`
### Rule 103
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-25/f3-1`
  - `www.tenant-shop.jp/chintai_biz/pa-25/f3-1/shin-1`
- `target`: `/chintai/aichi/office`
### Rule 104
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-25/f4-1`
  - `www.tenant-shop.jp/chintai_biz/pa-25/f4-1/shin-1`
- `target`: `/chintai/aichi/retail`
### Rule 105
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-25/f5-1`
  - `www.tenant-shop.jp/chintai_biz/pa-25/f5-1/shin-1`
- `target`: `/chintai/aichi/warehouse`
### Rule 106
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-25/f6-1`
  - `www.tenant-shop.jp/chintai_biz/pa-25/f6-1/shin-1`
- `target`: `/chintai/aichi/beauty`
### Rule 107
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-25/f7-1`
  - `www.tenant-shop.jp/chintai_biz/pa-25/f7-1/shin-1`
- `target`: `/chintai/aichi/roadside`
### Rule 108
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-25/f8-1`
  - `www.tenant-shop.jp/chintai_biz/pa-25/f8-1/shin-1`
- `target`: `/chintai/aichi/mall`
### Rule 109
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-26`
  - `www.tenant-shop.jp/chintai_biz/pa-26/shin-1`
- `target`: `/chintai/gifu`
### Rule 110
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-26/f1-1`
  - `www.tenant-shop.jp/chintai_biz/pa-26/f1-1/shin-1`
- `target`: `/chintai/gifu/inuki`
### Rule 111
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-26/f2-1`
  - `www.tenant-shop.jp/chintai_biz/pa-26/f2-1/shin-1`
- `target`: `/chintai/gifu/food`
### Rule 112
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-26/f3-1`
  - `www.tenant-shop.jp/chintai_biz/pa-26/f3-1/shin-1`
- `target`: `/chintai/gifu/office`
### Rule 113
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-26/f4-1`
  - `www.tenant-shop.jp/chintai_biz/pa-26/f4-1/shin-1`
- `target`: `/chintai/gifu/retail`
### Rule 114
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-26/f5-1`
  - `www.tenant-shop.jp/chintai_biz/pa-26/f5-1/shin-1`
- `target`: `/chintai/gifu/warehouse`
### Rule 115
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-26/f6-1`
  - `www.tenant-shop.jp/chintai_biz/pa-26/f6-1/shin-1`
- `target`: `/chintai/gifu/beauty`
### Rule 116
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-26/f7-1`
  - `www.tenant-shop.jp/chintai_biz/pa-26/f7-1/shin-1`
- `target`: `/chintai/gifu/roadside`
### Rule 117
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-26/f8-1`
  - `www.tenant-shop.jp/chintai_biz/pa-26/f8-1/shin-1`
- `target`: `/chintai/gifu/mall`
### Rule 118
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-27`
  - `www.tenant-shop.jp/chintai_biz/pa-27/shin-1`
- `target`: `/chintai/shizuoka`
### Rule 119
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-27/f1-1`
  - `www.tenant-shop.jp/chintai_biz/pa-27/f1-1/shin-1`
- `target`: `/chintai/shizuoka/inuki`
### Rule 120
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-27/f2-1`
  - `www.tenant-shop.jp/chintai_biz/pa-27/f2-1/shin-1`
- `target`: `/chintai/shizuoka/food`
### Rule 121
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-27/f3-1`
  - `www.tenant-shop.jp/chintai_biz/pa-27/f3-1/shin-1`
- `target`: `/chintai/shizuoka/office`
### Rule 122
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-27/f4-1`
  - `www.tenant-shop.jp/chintai_biz/pa-27/f4-1/shin-1`
- `target`: `/chintai/shizuoka/retail`
### Rule 123
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-27/f5-1`
  - `www.tenant-shop.jp/chintai_biz/pa-27/f5-1/shin-1`
- `target`: `/chintai/shizuoka/warehouse`
### Rule 124
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-27/f6-1`
  - `www.tenant-shop.jp/chintai_biz/pa-27/f6-1/shin-1`
- `target`: `/chintai/shizuoka/beauty`
### Rule 125
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-27/f7-1`
  - `www.tenant-shop.jp/chintai_biz/pa-27/f7-1/shin-1`
- `target`: `/chintai/shizuoka/roadside`
### Rule 126
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-27/f8-1`
  - `www.tenant-shop.jp/chintai_biz/pa-27/f8-1/shin-1`
- `target`: `/chintai/shizuoka/mall`
### Rule 127
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-1`
  - `www.tenant-shop.jp/chintai_biz/pa-1/shin-1`
- `target`: `/chintai/osaka`
### Rule 128
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-1/f1-1`
  - `www.tenant-shop.jp/chintai_biz/pa-1/f1-1/shin-1`
- `target`: `/chintai/osaka/inuki`
### Rule 129
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-1/f2-1`
  - `www.tenant-shop.jp/chintai_biz/pa-1/f2-1/shin-1`
- `target`: `/chintai/osaka/food`
### Rule 130
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-1/f3-1`
  - `www.tenant-shop.jp/chintai_biz/pa-1/f3-1/shin-1`
- `target`: `/chintai/osaka/office`
### Rule 131
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-1/f4-1`
  - `www.tenant-shop.jp/chintai_biz/pa-1/f4-1/shin-1`
- `target`: `/chintai/osaka/retail`
### Rule 132
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-1/f5-1`
  - `www.tenant-shop.jp/chintai_biz/pa-1/f5-1/shin-1`
- `target`: `/chintai/osaka/warehouse`
### Rule 133
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-1/f6-1`
  - `www.tenant-shop.jp/chintai_biz/pa-1/f6-1/shin-1`
- `target`: `/chintai/osaka/beauty`
### Rule 134
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-1/f7-1`
  - `www.tenant-shop.jp/chintai_biz/pa-1/f7-1/shin-1`
- `target`: `/chintai/osaka/roadside`
### Rule 135
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-1/f8-1`
  - `www.tenant-shop.jp/chintai_biz/pa-1/f8-1/shin-1`
- `target`: `/chintai/osaka/mall`
### Rule 136
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-31`
  - `www.tenant-shop.jp/chintai_biz/pa-31/shin-1`
- `target`: `/chintai/kyoto`
### Rule 137
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-31/f1-1`
  - `www.tenant-shop.jp/chintai_biz/pa-31/f1-1/shin-1`
- `target`: `/chintai/kyoto/inuki`
### Rule 138
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-31/f2-1`
  - `www.tenant-shop.jp/chintai_biz/pa-31/f2-1/shin-1`
- `target`: `/chintai/kyoto/food`
### Rule 139
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-31/f3-1`
  - `www.tenant-shop.jp/chintai_biz/pa-31/f3-1/shin-1`
- `target`: `/chintai/kyoto/office`
### Rule 140
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-31/f4-1`
  - `www.tenant-shop.jp/chintai_biz/pa-31/f4-1/shin-1`
- `target`: `/chintai/kyoto/retail`
### Rule 141
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-31/f5-1`
  - `www.tenant-shop.jp/chintai_biz/pa-31/f5-1/shin-1`
- `target`: `/chintai/kyoto/warehouse`
### Rule 142
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-31/f6-1`
  - `www.tenant-shop.jp/chintai_biz/pa-31/f6-1/shin-1`
- `target`: `/chintai/kyoto/beauty`
### Rule 143
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-31/f7-1`
  - `www.tenant-shop.jp/chintai_biz/pa-31/f7-1/shin-1`
- `target`: `/chintai/kyoto/roadside`
### Rule 144
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-31/f8-1`
  - `www.tenant-shop.jp/chintai_biz/pa-31/f8-1/shin-1`
- `target`: `/chintai/kyoto/mall`
### Rule 145
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-32`
  - `www.tenant-shop.jp/chintai_biz/pa-32/shin-1`
- `target`: `/chintai/hyogo`
### Rule 146
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-32/f1-1`
  - `www.tenant-shop.jp/chintai_biz/pa-32/f1-1/shin-1`
- `target`: `/chintai/hyogo/inuki`
### Rule 147
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-32/f2-1`
  - `www.tenant-shop.jp/chintai_biz/pa-32/f2-1/shin-1`
- `target`: `/chintai/hyogo/food`
### Rule 148
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-32/f3-1`
  - `www.tenant-shop.jp/chintai_biz/pa-32/f3-1/shin-1`
- `target`: `/chintai/hyogo/office`
### Rule 149
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-32/f4-1`
  - `www.tenant-shop.jp/chintai_biz/pa-32/f4-1/shin-1`
- `target`: `/chintai/hyogo/retail`
### Rule 150
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-32/f5-1`
  - `www.tenant-shop.jp/chintai_biz/pa-32/f5-1/shin-1`
- `target`: `/chintai/hyogo/warehouse`
### Rule 151
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-32/f6-1`
  - `www.tenant-shop.jp/chintai_biz/pa-32/f6-1/shin-1`
- `target`: `/chintai/hyogo/beauty`
### Rule 152
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-32/f7-1`
  - `www.tenant-shop.jp/chintai_biz/pa-32/f7-1/shin-1`
- `target`: `/chintai/hyogo/roadside`
### Rule 153
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-32/f8-1`
  - `www.tenant-shop.jp/chintai_biz/pa-32/f8-1/shin-1`
- `target`: `/chintai/hyogo/mall`
### Rule 154
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-5`
  - `www.tenant-shop.jp/chintai_biz/pa-5/shin-1`
- `target`: `/chintai/shiga`
### Rule 155
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-5/f1-1`
  - `www.tenant-shop.jp/chintai_biz/pa-5/f1-1/shin-1`
- `target`: `/chintai/shiga/inuki`
### Rule 156
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-5/f2-1`
  - `www.tenant-shop.jp/chintai_biz/pa-5/f2-1/shin-1`
- `target`: `/chintai/shiga/food`
### Rule 157
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-5/f3-1`
  - `www.tenant-shop.jp/chintai_biz/pa-5/f3-1/shin-1`
- `target`: `/chintai/shiga/office`
### Rule 158
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-5/f4-1`
  - `www.tenant-shop.jp/chintai_biz/pa-5/f4-1/shin-1`
- `target`: `/chintai/shiga/retail`
### Rule 159
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-5/f5-1`
  - `www.tenant-shop.jp/chintai_biz/pa-5/f5-1/shin-1`
- `target`: `/chintai/shiga/warehouse`
### Rule 160
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-5/f6-1`
  - `www.tenant-shop.jp/chintai_biz/pa-5/f6-1/shin-1`
- `target`: `/chintai/shiga/beauty`
### Rule 161
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-5/f7-1`
  - `www.tenant-shop.jp/chintai_biz/pa-5/f7-1/shin-1`
- `target`: `/chintai/shiga/roadside`
### Rule 162
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-5/f8-1`
  - `www.tenant-shop.jp/chintai_biz/pa-5/f8-1/shin-1`
- `target`: `/chintai/shiga/mall`
### Rule 163
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-34`
  - `www.tenant-shop.jp/chintai_biz/pa-34/shin-1`
- `target`: `/chintai/nara`
### Rule 164
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-34/f1-1`
  - `www.tenant-shop.jp/chintai_biz/pa-34/f1-1/shin-1`
- `target`: `/chintai/nara/inuki`
### Rule 165
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-34/f2-1`
  - `www.tenant-shop.jp/chintai_biz/pa-34/f2-1/shin-1`
- `target`: `/chintai/nara/food`
### Rule 166
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-34/f3-1`
  - `www.tenant-shop.jp/chintai_biz/pa-34/f3-1/shin-1`
- `target`: `/chintai/nara/office`
### Rule 167
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-34/f4-1`
  - `www.tenant-shop.jp/chintai_biz/pa-34/f4-1/shin-1`
- `target`: `/chintai/nara/retail`
### Rule 168
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-34/f5-1`
  - `www.tenant-shop.jp/chintai_biz/pa-34/f5-1/shin-1`
- `target`: `/chintai/nara/warehouse`
### Rule 169
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-34/f6-1`
  - `www.tenant-shop.jp/chintai_biz/pa-34/f6-1/shin-1`
- `target`: `/chintai/nara/beauty`
### Rule 170
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-34/f7-1`
  - `www.tenant-shop.jp/chintai_biz/pa-34/f7-1/shin-1`
- `target`: `/chintai/nara/roadside`
### Rule 171
- `source`:
  - `www.tenant-shop.jp/chintai_biz/pa-34/f8-1`
  - `www.tenant-shop.jp/chintai_biz/pa-34/f8-1/shin-1`
- `target`: `/chintai/nara/mall`

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
        "www.tenant-shop.com/chintai_biz/pa-14",
        "www.tenant-shop.com/chintai_biz/pa-14/shin-1"
      ],
      "target": "/chintai/tokyo"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-14/f1-1",
        "www.tenant-shop.com/chintai_biz/pa-14/f1-1/shin-1"
      ],
      "target": "/chintai/tokyo/inuki"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-14/f2-1",
        "www.tenant-shop.com/chintai_biz/pa-14/f2-1/shin-1"
      ],
      "target": "/chintai/tokyo/food"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-14/f3-1",
        "www.tenant-shop.com/chintai_biz/pa-14/f3-1/shin-1"
      ],
      "target": "/chintai/tokyo/office"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-14/f4-1",
        "www.tenant-shop.com/chintai_biz/pa-14/f4-1/shin-1"
      ],
      "target": "/chintai/tokyo/retail"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-14/f5-1",
        "www.tenant-shop.com/chintai_biz/pa-14/f5-1/shin-1"
      ],
      "target": "/chintai/tokyo/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-14/f6-1",
        "www.tenant-shop.com/chintai_biz/pa-14/f6-1/shin-1"
      ],
      "target": "/chintai/tokyo/beauty"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-14/f7-1",
        "www.tenant-shop.com/chintai_biz/pa-14/f7-1/shin-1"
      ],
      "target": "/chintai/tokyo/roadside"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-14/f8-1",
        "www.tenant-shop.com/chintai_biz/pa-14/f8-1/shin-1"
      ],
      "target": "/chintai/tokyo/mall"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-15",
        "www.tenant-shop.com/chintai_biz/pa-15/shin-1"
      ],
      "target": "/chintai/kanagawa"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-15/f1-1",
        "www.tenant-shop.com/chintai_biz/pa-15/f1-1/shin-1"
      ],
      "target": "/chintai/kanagawa/inuki"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-15/f2-1",
        "www.tenant-shop.com/chintai_biz/pa-15/f2-1/shin-1"
      ],
      "target": "/chintai/kanagawa/food"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-15/f3-1",
        "www.tenant-shop.com/chintai_biz/pa-15/f3-1/shin-1"
      ],
      "target": "/chintai/kanagawa/office"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-15/f4-1",
        "www.tenant-shop.com/chintai_biz/pa-15/f4-1/shin-1"
      ],
      "target": "/chintai/kanagawa/retail"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-15/f5-1",
        "www.tenant-shop.com/chintai_biz/pa-15/f5-1/shin-1"
      ],
      "target": "/chintai/kanagawa/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-15/f6-1",
        "www.tenant-shop.com/chintai_biz/pa-15/f6-1/shin-1"
      ],
      "target": "/chintai/kanagawa/beauty"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-15/f7-1",
        "www.tenant-shop.com/chintai_biz/pa-15/f7-1/shin-1"
      ],
      "target": "/chintai/kanagawa/roadside"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-15/f8-1",
        "www.tenant-shop.com/chintai_biz/pa-15/f8-1/shin-1"
      ],
      "target": "/chintai/kanagawa/mall"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-16",
        "www.tenant-shop.com/chintai_biz/pa-16/shin-1"
      ],
      "target": "/chintai/saitama"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-16/f1-1",
        "www.tenant-shop.com/chintai_biz/pa-16/f1-1/shin-1"
      ],
      "target": "/chintai/saitama/inuki"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-16/f2-1",
        "www.tenant-shop.com/chintai_biz/pa-16/f2-1/shin-1"
      ],
      "target": "/chintai/saitama/food"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-16/f3-1",
        "www.tenant-shop.com/chintai_biz/pa-16/f3-1/shin-1"
      ],
      "target": "/chintai/saitama/office"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-16/f4-1",
        "www.tenant-shop.com/chintai_biz/pa-16/f4-1/shin-1"
      ],
      "target": "/chintai/saitama/retail"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-16/f5-1",
        "www.tenant-shop.com/chintai_biz/pa-16/f5-1/shin-1"
      ],
      "target": "/chintai/saitama/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-16/f6-1",
        "www.tenant-shop.com/chintai_biz/pa-16/f6-1/shin-1"
      ],
      "target": "/chintai/saitama/beauty"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-16/f7-1",
        "www.tenant-shop.com/chintai_biz/pa-16/f7-1/shin-1"
      ],
      "target": "/chintai/saitama/roadside"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-16/f8-1",
        "www.tenant-shop.com/chintai_biz/pa-16/f8-1/shin-1"
      ],
      "target": "/chintai/saitama/mall"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-17",
        "www.tenant-shop.com/chintai_biz/pa-17/shin-1"
      ],
      "target": "/chintai/chiba"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-17/f1-1",
        "www.tenant-shop.com/chintai_biz/pa-17/f1-1/shin-1"
      ],
      "target": "/chintai/chiba/inuki"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-17/f2-1",
        "www.tenant-shop.com/chintai_biz/pa-17/f2-1/shin-1"
      ],
      "target": "/chintai/chiba/food"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-17/f3-1",
        "www.tenant-shop.com/chintai_biz/pa-17/f3-1/shin-1"
      ],
      "target": "/chintai/chiba/office"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-17/f4-1",
        "www.tenant-shop.com/chintai_biz/pa-17/f4-1/shin-1"
      ],
      "target": "/chintai/chiba/retail"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-17/f5-1",
        "www.tenant-shop.com/chintai_biz/pa-17/f5-1/shin-1"
      ],
      "target": "/chintai/chiba/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-17/f6-1",
        "www.tenant-shop.com/chintai_biz/pa-17/f6-1/shin-1"
      ],
      "target": "/chintai/chiba/beauty"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-17/f7-1",
        "www.tenant-shop.com/chintai_biz/pa-17/f7-1/shin-1"
      ],
      "target": "/chintai/chiba/roadside"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-17/f8-1",
        "www.tenant-shop.com/chintai_biz/pa-17/f8-1/shin-1"
      ],
      "target": "/chintai/chiba/mall"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-18",
        "www.tenant-shop.com/chintai_biz/pa-18/shin-1"
      ],
      "target": "/chintai/ibaraki"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-18/f1-1",
        "www.tenant-shop.com/chintai_biz/pa-18/f1-1/shin-1"
      ],
      "target": "/chintai/ibaraki/inuki"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-18/f2-1",
        "www.tenant-shop.com/chintai_biz/pa-18/f2-1/shin-1"
      ],
      "target": "/chintai/ibaraki/food"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-18/f3-1",
        "www.tenant-shop.com/chintai_biz/pa-18/f3-1/shin-1"
      ],
      "target": "/chintai/ibaraki/office"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-18/f4-1",
        "www.tenant-shop.com/chintai_biz/pa-18/f4-1/shin-1"
      ],
      "target": "/chintai/ibaraki/retail"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-18/f5-1",
        "www.tenant-shop.com/chintai_biz/pa-18/f5-1/shin-1"
      ],
      "target": "/chintai/ibaraki/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-18/f6-1",
        "www.tenant-shop.com/chintai_biz/pa-18/f6-1/shin-1"
      ],
      "target": "/chintai/ibaraki/beauty"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-18/f7-1",
        "www.tenant-shop.com/chintai_biz/pa-18/f7-1/shin-1"
      ],
      "target": "/chintai/ibaraki/roadside"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-18/f8-1",
        "www.tenant-shop.com/chintai_biz/pa-18/f8-1/shin-1"
      ],
      "target": "/chintai/ibaraki/mall"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-19",
        "www.tenant-shop.com/chintai_biz/pa-19/shin-1"
      ],
      "target": "/chintai/tochigi"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-19/f1-1",
        "www.tenant-shop.com/chintai_biz/pa-19/f1-1/shin-1"
      ],
      "target": "/chintai/tochigi/inuki"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-19/f2-1",
        "www.tenant-shop.com/chintai_biz/pa-19/f2-1/shin-1"
      ],
      "target": "/chintai/tochigi/food"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-19/f3-1",
        "www.tenant-shop.com/chintai_biz/pa-19/f3-1/shin-1"
      ],
      "target": "/chintai/tochigi/office"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-19/f4-1",
        "www.tenant-shop.com/chintai_biz/pa-19/f4-1/shin-1"
      ],
      "target": "/chintai/tochigi/retail"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-19/f5-1",
        "www.tenant-shop.com/chintai_biz/pa-19/f5-1/shin-1"
      ],
      "target": "/chintai/tochigi/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-19/f6-1",
        "www.tenant-shop.com/chintai_biz/pa-19/f6-1/shin-1"
      ],
      "target": "/chintai/tochigi/beauty"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-19/f7-1",
        "www.tenant-shop.com/chintai_biz/pa-19/f7-1/shin-1"
      ],
      "target": "/chintai/tochigi/roadside"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-19/f8-1",
        "www.tenant-shop.com/chintai_biz/pa-19/f8-1/shin-1"
      ],
      "target": "/chintai/tochigi/mall"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-20",
        "www.tenant-shop.com/chintai_biz/pa-20/shin-1"
      ],
      "target": "/chintai/gunma"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-20/f1-1",
        "www.tenant-shop.com/chintai_biz/pa-20/f1-1/shin-1"
      ],
      "target": "/chintai/gunma/inuki"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-20/f2-1",
        "www.tenant-shop.com/chintai_biz/pa-20/f2-1/shin-1"
      ],
      "target": "/chintai/gunma/food"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-20/f3-1",
        "www.tenant-shop.com/chintai_biz/pa-20/f3-1/shin-1"
      ],
      "target": "/chintai/gunma/office"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-20/f4-1",
        "www.tenant-shop.com/chintai_biz/pa-20/f4-1/shin-1"
      ],
      "target": "/chintai/gunma/retail"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-20/f5-1",
        "www.tenant-shop.com/chintai_biz/pa-20/f5-1/shin-1"
      ],
      "target": "/chintai/gunma/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-20/f6-1",
        "www.tenant-shop.com/chintai_biz/pa-20/f6-1/shin-1"
      ],
      "target": "/chintai/gunma/beauty"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-20/f7-1",
        "www.tenant-shop.com/chintai_biz/pa-20/f7-1/shin-1"
      ],
      "target": "/chintai/gunma/roadside"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-20/f8-1",
        "www.tenant-shop.com/chintai_biz/pa-20/f8-1/shin-1"
      ],
      "target": "/chintai/gunma/mall"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-7",
        "www.tenant-shop.com/chintai_biz/pa-7/shin-1"
      ],
      "target": "/chintai/hokkaido"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-7/f1-1",
        "www.tenant-shop.com/chintai_biz/pa-7/f1-1/shin-1"
      ],
      "target": "/chintai/hokkaido/inuki"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-7/f2-1",
        "www.tenant-shop.com/chintai_biz/pa-7/f2-1/shin-1"
      ],
      "target": "/chintai/hokkaido/food"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-7/f3-1",
        "www.tenant-shop.com/chintai_biz/pa-7/f3-1/shin-1"
      ],
      "target": "/chintai/hokkaido/office"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-7/f4-1",
        "www.tenant-shop.com/chintai_biz/pa-7/f4-1/shin-1"
      ],
      "target": "/chintai/hokkaido/retail"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-7/f5-1",
        "www.tenant-shop.com/chintai_biz/pa-7/f5-1/shin-1"
      ],
      "target": "/chintai/hokkaido/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-7/f6-1",
        "www.tenant-shop.com/chintai_biz/pa-7/f6-1/shin-1"
      ],
      "target": "/chintai/hokkaido/beauty"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-7/f7-1",
        "www.tenant-shop.com/chintai_biz/pa-7/f7-1/shin-1"
      ],
      "target": "/chintai/hokkaido/roadside"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-7/f8-1",
        "www.tenant-shop.com/chintai_biz/pa-7/f8-1/shin-1"
      ],
      "target": "/chintai/hokkaido/mall"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-10",
        "www.tenant-shop.com/chintai_biz/pa-10/shin-1"
      ],
      "target": "/chintai/miyagi"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-10/f1-1",
        "www.tenant-shop.com/chintai_biz/pa-10/f1-1/shin-1"
      ],
      "target": "/chintai/miyagi/inuki"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-10/f2-1",
        "www.tenant-shop.com/chintai_biz/pa-10/f2-1/shin-1"
      ],
      "target": "/chintai/miyagi/food"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-10/f3-1",
        "www.tenant-shop.com/chintai_biz/pa-10/f3-1/shin-1"
      ],
      "target": "/chintai/miyagi/office"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-10/f4-1",
        "www.tenant-shop.com/chintai_biz/pa-10/f4-1/shin-1"
      ],
      "target": "/chintai/miyagi/retail"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-10/f5-1",
        "www.tenant-shop.com/chintai_biz/pa-10/f5-1/shin-1"
      ],
      "target": "/chintai/miyagi/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-10/f6-1",
        "www.tenant-shop.com/chintai_biz/pa-10/f6-1/shin-1"
      ],
      "target": "/chintai/miyagi/beauty"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-10/f7-1",
        "www.tenant-shop.com/chintai_biz/pa-10/f7-1/shin-1"
      ],
      "target": "/chintai/miyagi/roadside"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-10/f8-1",
        "www.tenant-shop.com/chintai_biz/pa-10/f8-1/shin-1"
      ],
      "target": "/chintai/miyagi/mall"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-21",
        "www.tenant-shop.com/chintai_biz/pa-21/shin-1"
      ],
      "target": "/chintai/niigata"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-21/f1-1",
        "www.tenant-shop.com/chintai_biz/pa-21/f1-1/shin-1"
      ],
      "target": "/chintai/niigata/inuki"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-21/f2-1",
        "www.tenant-shop.com/chintai_biz/pa-21/f2-1/shin-1"
      ],
      "target": "/chintai/niigata/food"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-21/f3-1",
        "www.tenant-shop.com/chintai_biz/pa-21/f3-1/shin-1"
      ],
      "target": "/chintai/niigata/office"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-21/f4-1",
        "www.tenant-shop.com/chintai_biz/pa-21/f4-1/shin-1"
      ],
      "target": "/chintai/niigata/retail"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-21/f5-1",
        "www.tenant-shop.com/chintai_biz/pa-21/f5-1/shin-1"
      ],
      "target": "/chintai/niigata/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-21/f6-1",
        "www.tenant-shop.com/chintai_biz/pa-21/f6-1/shin-1"
      ],
      "target": "/chintai/niigata/beauty"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-21/f7-1",
        "www.tenant-shop.com/chintai_biz/pa-21/f7-1/shin-1"
      ],
      "target": "/chintai/niigata/roadside"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-21/f8-1",
        "www.tenant-shop.com/chintai_biz/pa-21/f8-1/shin-1"
      ],
      "target": "/chintai/niigata/mall"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-28",
        "www.tenant-shop.com/chintai_biz/pa-28/shin-1"
      ],
      "target": "/chintai/nagano"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-28/f1-1",
        "www.tenant-shop.com/chintai_biz/pa-28/f1-1/shin-1"
      ],
      "target": "/chintai/nagano/inuki"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-28/f2-1",
        "www.tenant-shop.com/chintai_biz/pa-28/f2-1/shin-1"
      ],
      "target": "/chintai/nagano/food"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-28/f3-1",
        "www.tenant-shop.com/chintai_biz/pa-28/f3-1/shin-1"
      ],
      "target": "/chintai/nagano/office"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-28/f4-1",
        "www.tenant-shop.com/chintai_biz/pa-28/f4-1/shin-1"
      ],
      "target": "/chintai/nagano/retail"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-28/f5-1",
        "www.tenant-shop.com/chintai_biz/pa-28/f5-1/shin-1"
      ],
      "target": "/chintai/nagano/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-28/f6-1",
        "www.tenant-shop.com/chintai_biz/pa-28/f6-1/shin-1"
      ],
      "target": "/chintai/nagano/beauty"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-28/f7-1",
        "www.tenant-shop.com/chintai_biz/pa-28/f7-1/shin-1"
      ],
      "target": "/chintai/nagano/roadside"
    },
    {
      "source": [
        "www.tenant-shop.com/chintai_biz/pa-28/f8-1",
        "www.tenant-shop.com/chintai_biz/pa-28/f8-1/shin-1"
      ],
      "target": "/chintai/nagano/mall"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-25",
        "www.tenant-shop.jp/chintai_biz/pa-25/shin-1"
      ],
      "target": "/chintai/aichi"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-25/f1-1",
        "www.tenant-shop.jp/chintai_biz/pa-25/f1-1/shin-1"
      ],
      "target": "/chintai/aichi/inuki"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-25/f2-1",
        "www.tenant-shop.jp/chintai_biz/pa-25/f2-1/shin-1"
      ],
      "target": "/chintai/aichi/food"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-25/f3-1",
        "www.tenant-shop.jp/chintai_biz/pa-25/f3-1/shin-1"
      ],
      "target": "/chintai/aichi/office"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-25/f4-1",
        "www.tenant-shop.jp/chintai_biz/pa-25/f4-1/shin-1"
      ],
      "target": "/chintai/aichi/retail"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-25/f5-1",
        "www.tenant-shop.jp/chintai_biz/pa-25/f5-1/shin-1"
      ],
      "target": "/chintai/aichi/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-25/f6-1",
        "www.tenant-shop.jp/chintai_biz/pa-25/f6-1/shin-1"
      ],
      "target": "/chintai/aichi/beauty"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-25/f7-1",
        "www.tenant-shop.jp/chintai_biz/pa-25/f7-1/shin-1"
      ],
      "target": "/chintai/aichi/roadside"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-25/f8-1",
        "www.tenant-shop.jp/chintai_biz/pa-25/f8-1/shin-1"
      ],
      "target": "/chintai/aichi/mall"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-26",
        "www.tenant-shop.jp/chintai_biz/pa-26/shin-1"
      ],
      "target": "/chintai/gifu"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-26/f1-1",
        "www.tenant-shop.jp/chintai_biz/pa-26/f1-1/shin-1"
      ],
      "target": "/chintai/gifu/inuki"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-26/f2-1",
        "www.tenant-shop.jp/chintai_biz/pa-26/f2-1/shin-1"
      ],
      "target": "/chintai/gifu/food"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-26/f3-1",
        "www.tenant-shop.jp/chintai_biz/pa-26/f3-1/shin-1"
      ],
      "target": "/chintai/gifu/office"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-26/f4-1",
        "www.tenant-shop.jp/chintai_biz/pa-26/f4-1/shin-1"
      ],
      "target": "/chintai/gifu/retail"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-26/f5-1",
        "www.tenant-shop.jp/chintai_biz/pa-26/f5-1/shin-1"
      ],
      "target": "/chintai/gifu/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-26/f6-1",
        "www.tenant-shop.jp/chintai_biz/pa-26/f6-1/shin-1"
      ],
      "target": "/chintai/gifu/beauty"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-26/f7-1",
        "www.tenant-shop.jp/chintai_biz/pa-26/f7-1/shin-1"
      ],
      "target": "/chintai/gifu/roadside"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-26/f8-1",
        "www.tenant-shop.jp/chintai_biz/pa-26/f8-1/shin-1"
      ],
      "target": "/chintai/gifu/mall"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-27",
        "www.tenant-shop.jp/chintai_biz/pa-27/shin-1"
      ],
      "target": "/chintai/shizuoka"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-27/f1-1",
        "www.tenant-shop.jp/chintai_biz/pa-27/f1-1/shin-1"
      ],
      "target": "/chintai/shizuoka/inuki"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-27/f2-1",
        "www.tenant-shop.jp/chintai_biz/pa-27/f2-1/shin-1"
      ],
      "target": "/chintai/shizuoka/food"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-27/f3-1",
        "www.tenant-shop.jp/chintai_biz/pa-27/f3-1/shin-1"
      ],
      "target": "/chintai/shizuoka/office"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-27/f4-1",
        "www.tenant-shop.jp/chintai_biz/pa-27/f4-1/shin-1"
      ],
      "target": "/chintai/shizuoka/retail"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-27/f5-1",
        "www.tenant-shop.jp/chintai_biz/pa-27/f5-1/shin-1"
      ],
      "target": "/chintai/shizuoka/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-27/f6-1",
        "www.tenant-shop.jp/chintai_biz/pa-27/f6-1/shin-1"
      ],
      "target": "/chintai/shizuoka/beauty"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-27/f7-1",
        "www.tenant-shop.jp/chintai_biz/pa-27/f7-1/shin-1"
      ],
      "target": "/chintai/shizuoka/roadside"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-27/f8-1",
        "www.tenant-shop.jp/chintai_biz/pa-27/f8-1/shin-1"
      ],
      "target": "/chintai/shizuoka/mall"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-1",
        "www.tenant-shop.jp/chintai_biz/pa-1/shin-1"
      ],
      "target": "/chintai/osaka"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-1/f1-1",
        "www.tenant-shop.jp/chintai_biz/pa-1/f1-1/shin-1"
      ],
      "target": "/chintai/osaka/inuki"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-1/f2-1",
        "www.tenant-shop.jp/chintai_biz/pa-1/f2-1/shin-1"
      ],
      "target": "/chintai/osaka/food"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-1/f3-1",
        "www.tenant-shop.jp/chintai_biz/pa-1/f3-1/shin-1"
      ],
      "target": "/chintai/osaka/office"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-1/f4-1",
        "www.tenant-shop.jp/chintai_biz/pa-1/f4-1/shin-1"
      ],
      "target": "/chintai/osaka/retail"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-1/f5-1",
        "www.tenant-shop.jp/chintai_biz/pa-1/f5-1/shin-1"
      ],
      "target": "/chintai/osaka/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-1/f6-1",
        "www.tenant-shop.jp/chintai_biz/pa-1/f6-1/shin-1"
      ],
      "target": "/chintai/osaka/beauty"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-1/f7-1",
        "www.tenant-shop.jp/chintai_biz/pa-1/f7-1/shin-1"
      ],
      "target": "/chintai/osaka/roadside"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-1/f8-1",
        "www.tenant-shop.jp/chintai_biz/pa-1/f8-1/shin-1"
      ],
      "target": "/chintai/osaka/mall"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-31",
        "www.tenant-shop.jp/chintai_biz/pa-31/shin-1"
      ],
      "target": "/chintai/kyoto"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-31/f1-1",
        "www.tenant-shop.jp/chintai_biz/pa-31/f1-1/shin-1"
      ],
      "target": "/chintai/kyoto/inuki"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-31/f2-1",
        "www.tenant-shop.jp/chintai_biz/pa-31/f2-1/shin-1"
      ],
      "target": "/chintai/kyoto/food"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-31/f3-1",
        "www.tenant-shop.jp/chintai_biz/pa-31/f3-1/shin-1"
      ],
      "target": "/chintai/kyoto/office"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-31/f4-1",
        "www.tenant-shop.jp/chintai_biz/pa-31/f4-1/shin-1"
      ],
      "target": "/chintai/kyoto/retail"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-31/f5-1",
        "www.tenant-shop.jp/chintai_biz/pa-31/f5-1/shin-1"
      ],
      "target": "/chintai/kyoto/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-31/f6-1",
        "www.tenant-shop.jp/chintai_biz/pa-31/f6-1/shin-1"
      ],
      "target": "/chintai/kyoto/beauty"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-31/f7-1",
        "www.tenant-shop.jp/chintai_biz/pa-31/f7-1/shin-1"
      ],
      "target": "/chintai/kyoto/roadside"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-31/f8-1",
        "www.tenant-shop.jp/chintai_biz/pa-31/f8-1/shin-1"
      ],
      "target": "/chintai/kyoto/mall"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-32",
        "www.tenant-shop.jp/chintai_biz/pa-32/shin-1"
      ],
      "target": "/chintai/hyogo"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-32/f1-1",
        "www.tenant-shop.jp/chintai_biz/pa-32/f1-1/shin-1"
      ],
      "target": "/chintai/hyogo/inuki"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-32/f2-1",
        "www.tenant-shop.jp/chintai_biz/pa-32/f2-1/shin-1"
      ],
      "target": "/chintai/hyogo/food"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-32/f3-1",
        "www.tenant-shop.jp/chintai_biz/pa-32/f3-1/shin-1"
      ],
      "target": "/chintai/hyogo/office"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-32/f4-1",
        "www.tenant-shop.jp/chintai_biz/pa-32/f4-1/shin-1"
      ],
      "target": "/chintai/hyogo/retail"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-32/f5-1",
        "www.tenant-shop.jp/chintai_biz/pa-32/f5-1/shin-1"
      ],
      "target": "/chintai/hyogo/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-32/f6-1",
        "www.tenant-shop.jp/chintai_biz/pa-32/f6-1/shin-1"
      ],
      "target": "/chintai/hyogo/beauty"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-32/f7-1",
        "www.tenant-shop.jp/chintai_biz/pa-32/f7-1/shin-1"
      ],
      "target": "/chintai/hyogo/roadside"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-32/f8-1",
        "www.tenant-shop.jp/chintai_biz/pa-32/f8-1/shin-1"
      ],
      "target": "/chintai/hyogo/mall"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-5",
        "www.tenant-shop.jp/chintai_biz/pa-5/shin-1"
      ],
      "target": "/chintai/shiga"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-5/f1-1",
        "www.tenant-shop.jp/chintai_biz/pa-5/f1-1/shin-1"
      ],
      "target": "/chintai/shiga/inuki"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-5/f2-1",
        "www.tenant-shop.jp/chintai_biz/pa-5/f2-1/shin-1"
      ],
      "target": "/chintai/shiga/food"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-5/f3-1",
        "www.tenant-shop.jp/chintai_biz/pa-5/f3-1/shin-1"
      ],
      "target": "/chintai/shiga/office"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-5/f4-1",
        "www.tenant-shop.jp/chintai_biz/pa-5/f4-1/shin-1"
      ],
      "target": "/chintai/shiga/retail"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-5/f5-1",
        "www.tenant-shop.jp/chintai_biz/pa-5/f5-1/shin-1"
      ],
      "target": "/chintai/shiga/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-5/f6-1",
        "www.tenant-shop.jp/chintai_biz/pa-5/f6-1/shin-1"
      ],
      "target": "/chintai/shiga/beauty"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-5/f7-1",
        "www.tenant-shop.jp/chintai_biz/pa-5/f7-1/shin-1"
      ],
      "target": "/chintai/shiga/roadside"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-5/f8-1",
        "www.tenant-shop.jp/chintai_biz/pa-5/f8-1/shin-1"
      ],
      "target": "/chintai/shiga/mall"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-34",
        "www.tenant-shop.jp/chintai_biz/pa-34/shin-1"
      ],
      "target": "/chintai/nara"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-34/f1-1",
        "www.tenant-shop.jp/chintai_biz/pa-34/f1-1/shin-1"
      ],
      "target": "/chintai/nara/inuki"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-34/f2-1",
        "www.tenant-shop.jp/chintai_biz/pa-34/f2-1/shin-1"
      ],
      "target": "/chintai/nara/food"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-34/f3-1",
        "www.tenant-shop.jp/chintai_biz/pa-34/f3-1/shin-1"
      ],
      "target": "/chintai/nara/office"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-34/f4-1",
        "www.tenant-shop.jp/chintai_biz/pa-34/f4-1/shin-1"
      ],
      "target": "/chintai/nara/retail"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-34/f5-1",
        "www.tenant-shop.jp/chintai_biz/pa-34/f5-1/shin-1"
      ],
      "target": "/chintai/nara/warehouse"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-34/f6-1",
        "www.tenant-shop.jp/chintai_biz/pa-34/f6-1/shin-1"
      ],
      "target": "/chintai/nara/beauty"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-34/f7-1",
        "www.tenant-shop.jp/chintai_biz/pa-34/f7-1/shin-1"
      ],
      "target": "/chintai/nara/roadside"
    },
    {
      "source": [
        "www.tenant-shop.jp/chintai_biz/pa-34/f8-1",
        "www.tenant-shop.jp/chintai_biz/pa-34/f8-1/shin-1"
      ],
      "target": "/chintai/nara/mall"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [],
  "url": "www.tenant-shop.com"
}
```
