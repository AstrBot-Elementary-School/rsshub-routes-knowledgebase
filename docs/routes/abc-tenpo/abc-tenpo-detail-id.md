# ABC Tenpo - 物件詳細

## Coverage
`index-only`

## Route
- Namespace: `abc-tenpo`
- Namespace Name: `ABC Tenpo`
- Route Path: `/abc-tenpo/detail/:id`
- Route Name: `物件詳細`
- Example: `/abc-tenpo/detail/62829`
- URL: `www.abc-tenpo.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `detail.ts`
- Source Module: `_None_`

## Description
One listing on ABC 店舗，for following a single property rather than a whole prefecture.

Its reason to exist is the address. The listing route can only reach the ward (`東京都文京区`) because the visible 所在地 field is truncated and marked 会員限定 — but the document title carries the address in full, `東京都文京区湯島2-31-17・…`, so `address_hint` here reaches the 丁目 **and the 番地**. That makes this one of the few sources that publishes a 番地 to a guest at all.

`_extra` follows the shared listing shape, including 現業態，業種制限，飲食条件 and the 居抜き / 重飲食可 tags; 構造，階建，席数 and 初期費用 are kept in `raw`. 保証金，礼金 and 造作譲渡料 are members-only on this site and stay `null`. The only date the site publishes is 情報更新日，so `listed_at` and `pubDate` are a last-modified date rather than a first-listed one — do not read them as a publication date.

## Parameters
- `id`: {"description": "The numeric 物件 id, i.e. the `62829` in `https://www.abc-tenpo.com/property/view/62829`"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.abc-tenpo.com/property/view/:id`
- `target`: `/detail/:id`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "One listing on ABC 店舗，for following a single property rather than a whole prefecture.\n\nIts reason to exist is the address. The listing route can only reach the ward (`東京都文京区`) because the visible 所在地 field is truncated and marked 会員限定 — but the document title carries the address in full, `東京都文京区湯島2-31-17・…`, so `address_hint` here reaches the 丁目 **and the 番地**. That makes this one of the few sources that publishes a 番地 to a guest at all.\n\n`_extra` follows the shared listing shape, including 現業態，業種制限，飲食条件 and the 居抜き / 重飲食可 tags; 構造，階建，席数 and 初期費用 are kept in `raw`. 保証金，礼金 and 造作譲渡料 are members-only on this site and stay `null`. The only date the site publishes is 情報更新日，so `listed_at` and `pubDate` are a last-modified date rather than a first-listed one — do not read them as a publication date.",
  "example": "/abc-tenpo/detail/62829",
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
      "description": "The numeric 物件 id, i.e. the `62829` in `https://www.abc-tenpo.com/property/view/62829`"
    }
  },
  "path": "/detail/:id",
  "radar": [
    {
      "source": [
        "www.abc-tenpo.com/property/view/:id"
      ],
      "target": "/detail/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.abc-tenpo.com"
}
```
