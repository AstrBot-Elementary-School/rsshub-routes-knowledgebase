# Inukitenpo - 居抜き物件

## Coverage
`index-only`

## Route
- Namespace: `i-tenpo`
- Namespace Name: `Inukitenpo`
- Route Path: `/i-tenpo/:pref/:city/:type?`
- Route Name: `居抜き物件`
- Example: `/i-tenpo/tokyo/shinjuku-city`
- URL: `www.i-tenpo.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `property.ts`
- Source Module: `_None_`

## Description
Listings on 居抜き店舗.com for one 市区町村 (first page, 20 listings), optionally narrowed to one 業態 — `/i-tenpo/tokyo/shinjuku-city/bar` is 新宿区のバー.

Each item's `_extra` follows the shared listing shape (賃料，坪，坪単価，階層，最寄駅，造作価格，前業態，引渡状態，…); unknown values are `null`. 敷金，礼金 and the coordinates are shown only to signed-in users and are therefore always `null`, the 丁目 appears only on the detail page so `address_hint` stops at the 町，and the cards carry no 登録日 so items have no `pubDate`.

引渡状態 combines two things — 営業状況 (`閉店済` / `営業中` / `確認中` / `新築`) and 引渡形態 (`居抜き` / `スケルトン` / `現状渡し`). Only the 引渡形態 half maps to `condition`, so `現状渡し` yields `null` rather than being forced into 居抜き or スケルトン；the whole string stays in `raw.handover`, which is where the 閉店済 closure signal can be read. Likewise 造作価格 `造作なし` / `造作無償` become `0` because they really are zero, while `確認中` stays `null` because it is unknown.

An unknown 市区町村 slug is answered by the site with the whole prefecture at HTTP 200 rather than a 404, so the route checks the area the page actually resolved and fails instead of silently serving prefecture-wide listings as if they were one ward's.

## Parameters
- `pref`: {"description": "都道府県 slug, e.g. `tokyo`, `kanagawa`"}
- `city`: {"description": "市区町村 slug as the site spells it — `shinjuku-city`, `minato-city`, `yokohamashinaka-city`"}
- `type`: {"description": "Optional 業態 slug, e.g. `bar`, `izakaya`, `cafe`, `restaurant`, `other-restaurants`; omit for every 業態"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.i-tenpo.com/:pref/:city/:type`
- `target`: `/:pref/:city/:type`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Listings on 居抜き店舗.com for one 市区町村 (first page, 20 listings), optionally narrowed to one 業態 — `/i-tenpo/tokyo/shinjuku-city/bar` is 新宿区のバー.\n\nEach item's `_extra` follows the shared listing shape (賃料，坪，坪単価，階層，最寄駅，造作価格，前業態，引渡状態，…); unknown values are `null`. 敷金，礼金 and the coordinates are shown only to signed-in users and are therefore always `null`, the 丁目 appears only on the detail page so `address_hint` stops at the 町，and the cards carry no 登録日 so items have no `pubDate`.\n\n引渡状態 combines two things — 営業状況 (`閉店済` / `営業中` / `確認中` / `新築`) and 引渡形態 (`居抜き` / `スケルトン` / `現状渡し`). Only the 引渡形態 half maps to `condition`, so `現状渡し` yields `null` rather than being forced into 居抜き or スケルトン；the whole string stays in `raw.handover`, which is where the 閉店済 closure signal can be read. Likewise 造作価格 `造作なし` / `造作無償` become `0` because they really are zero, while `確認中` stays `null` because it is unknown.\n\nAn unknown 市区町村 slug is answered by the site with the whole prefecture at HTTP 200 rather than a 404, so the route checks the area the page actually resolved and fails instead of silently serving prefecture-wide listings as if they were one ward's.",
  "example": "/i-tenpo/tokyo/shinjuku-city",
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
  "name": "居抜き物件",
  "parameters": {
    "city": {
      "description": "市区町村 slug as the site spells it — `shinjuku-city`, `minato-city`, `yokohamashinaka-city`"
    },
    "pref": {
      "description": "都道府県 slug, e.g. `tokyo`, `kanagawa`"
    },
    "type": {
      "description": "Optional 業態 slug, e.g. `bar`, `izakaya`, `cafe`, `restaurant`, `other-restaurants`; omit for every 業態"
    }
  },
  "path": "/:pref/:city/:type?",
  "radar": [
    {
      "source": [
        "www.i-tenpo.com/:pref/:city/:type"
      ],
      "target": "/:pref/:city/:type"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.i-tenpo.com"
}
```
