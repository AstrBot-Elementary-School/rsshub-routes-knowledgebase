# Inukitenpo - 物件詳細

## Coverage
`index-only`

## Route
- Namespace: `i-tenpo`
- Namespace Name: `Inukitenpo`
- Route Path: `/i-tenpo/detail/:id`
- Route Name: `物件詳細`
- Example: `/i-tenpo/detail/99523`
- URL: `www.i-tenpo.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `detail.ts`
- Source Module: `_None_`

## Description
One listing on 居抜き店舗.com, for following a single property rather than a whole ward — a listing's 賃料，引渡状態 and availability all change over its life.

Its one advantage over the ward routes is the address. The page's own 所在地 field stops at the 町 exactly as the list does (`東京都新宿区高田馬場 詳細はログイン後に表示`), but the document title carries the 丁目 — `新宿区高田馬場2丁目/高田馬場駅徒歩2分/…` — so `address_hint` reaches the 丁目 here and only here.

`_extra` follows the shared listing shape. 敷金 and 礼金 are shown only to signed-in users, here as on the list page, so they stay `null`. The site publishes 更新日 but no 掲載日，so `listed_at` and `pubDate` are a last-modified date rather than a first-listed one — do not read them as a publication date.

## Parameters
- `id`: {"description": "The numeric 物件 id, i.e. the `99523` in `https://www.i-tenpo.com/t99523`"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.i-tenpo.com/t:id`
- `target`: `/detail/:id`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "One listing on 居抜き店舗.com, for following a single property rather than a whole ward — a listing's 賃料，引渡状態 and availability all change over its life.\n\nIts one advantage over the ward routes is the address. The page's own 所在地 field stops at the 町 exactly as the list does (`東京都新宿区高田馬場 詳細はログイン後に表示`), but the document title carries the 丁目 — `新宿区高田馬場2丁目/高田馬場駅徒歩2分/…` — so `address_hint` reaches the 丁目 here and only here.\n\n`_extra` follows the shared listing shape. 敷金 and 礼金 are shown only to signed-in users, here as on the list page, so they stay `null`. The site publishes 更新日 but no 掲載日，so `listed_at` and `pubDate` are a last-modified date rather than a first-listed one — do not read them as a publication date.",
  "example": "/i-tenpo/detail/99523",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "detail.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "物件詳細",
  "parameters": {
    "id": {
      "description": "The numeric 物件 id, i.e. the `99523` in `https://www.i-tenpo.com/t99523`"
    }
  },
  "path": "/detail/:id",
  "radar": [
    {
      "source": [
        "www.i-tenpo.com/t:id"
      ],
      "target": "/detail/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.i-tenpo.com"
}
```
