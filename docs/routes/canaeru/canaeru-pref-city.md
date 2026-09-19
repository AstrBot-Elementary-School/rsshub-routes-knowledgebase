# Canaeru - 居抜き・貸店舗物件

## Coverage
`index-only`

## Route
- Namespace: `canaeru`
- Namespace Name: `Canaeru`
- Route Path: `/canaeru/:pref?/:city?`
- Route Name: `居抜き・貸店舗物件`
- Example: `/canaeru/tokyo/13104`
- URL: `canaeru.usen.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `property.ts`
- Source Module: `_None_`

## Description
Listings on canaeru（USEN）for one prefecture — or one 市区町村 when `city` is given (`/canaeru/tokyo/13104` is 新宿区). Each item's `_extra` carries the shared listing fields (賃料，坪，坪単価，階，最寄駅，保証金，礼金，造作価格，現況，…) from the list and detail pages; unknown values are `null`, and the site's 「ー」 placeholder is treated as unknown rather than kept as text.

Two things this source does better than most: 住所 is published down to the 番地 rather than the 町，and the detail page carries map coordinates. `ListingExtra` has no coordinate fields, so they are passed through verbatim as `raw.lat` / `raw.lng`.

`tags` are the site's own feature flags, keeping only those a listing actually has — the markup lists every flag and greys the rest out with `class="off"` — and 居抜き / スケルトン among them is what sets `condition`.

One caveat on 造作価格: the publisher occasionally appends 万円 to a figure that is already in 円 (one listing reads `6,050,000万円`), so `fixtures_transfer_jpy` can carry an implausible value. The route parses what is published rather than second-guessing it, so treat `raw.fixtures` as the ground truth when the number looks wrong.

関西 is not offered: the site serves it from a separate base path that could not be reached (`/bukken/osaka`, `/bukken_k/osaka` and `/bukken_o/osaka` all 404).

| Query   | Description                                                                  | Default |
| ------- | ---------------------------------------------------------------------------- | ------- |
| `limit` | Number of listings to process (detail pages are fetched per listing), max 10 | 10      |

## Parameters
- `pref`: {"default": "tokyo", "description": "Prefecture", "options": [{"label": "東京都", "value": "tokyo"}, {"label": "神奈川県", "value": "kanagawa"}, {"label": "埼玉県", "value": "saitama"}, {"label": "千葉県", "value": "chiba"}, {"label": "北海道", "value": "hokkaido"}, {"label": "愛知県", "value": "aichi"}, {"label": "静岡県", "value": "shizuoka"}]}
- `city`: {"description": "Optional 市区町村, as a 5-digit JIS X 0402 code (新宿区 `13104`, 港区 `13103`, 横浜市中区 `14104`). Must belong to `pref`; omit for the whole prefecture."}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `canaeru.usen.com/bukken/:pref/search/:city`
  - `canaeru.usen.com/bukken/:pref/search`
- `target`: `/:pref`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Listings on canaeru（USEN）for one prefecture — or one 市区町村 when `city` is given (`/canaeru/tokyo/13104` is 新宿区). Each item's `_extra` carries the shared listing fields (賃料，坪，坪単価，階，最寄駅，保証金，礼金，造作価格，現況，…) from the list and detail pages; unknown values are `null`, and the site's 「ー」 placeholder is treated as unknown rather than kept as text.\n\nTwo things this source does better than most: 住所 is published down to the 番地 rather than the 町，and the detail page carries map coordinates. `ListingExtra` has no coordinate fields, so they are passed through verbatim as `raw.lat` / `raw.lng`.\n\n`tags` are the site's own feature flags, keeping only those a listing actually has — the markup lists every flag and greys the rest out with `class=\"off\"` — and 居抜き / スケルトン among them is what sets `condition`.\n\nOne caveat on 造作価格: the publisher occasionally appends 万円 to a figure that is already in 円 (one listing reads `6,050,000万円`), so `fixtures_transfer_jpy` can carry an implausible value. The route parses what is published rather than second-guessing it, so treat `raw.fixtures` as the ground truth when the number looks wrong.\n\n関西 is not offered: the site serves it from a separate base path that could not be reached (`/bukken/osaka`, `/bukken_k/osaka` and `/bukken_o/osaka` all 404).\n\n| Query   | Description                                                                  | Default |\n| ------- | ---------------------------------------------------------------------------- | ------- |\n| `limit` | Number of listings to process (detail pages are fetched per listing), max 10 | 10      |",
  "example": "/canaeru/tokyo/13104",
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
  "name": "居抜き・貸店舗物件",
  "parameters": {
    "city": {
      "description": "Optional 市区町村, as a 5-digit JIS X 0402 code (新宿区 `13104`, 港区 `13103`, 横浜市中区 `14104`). Must belong to `pref`; omit for the whole prefecture."
    },
    "pref": {
      "default": "tokyo",
      "description": "Prefecture",
      "options": [
        {
          "label": "東京都",
          "value": "tokyo"
        },
        {
          "label": "神奈川県",
          "value": "kanagawa"
        },
        {
          "label": "埼玉県",
          "value": "saitama"
        },
        {
          "label": "千葉県",
          "value": "chiba"
        },
        {
          "label": "北海道",
          "value": "hokkaido"
        },
        {
          "label": "愛知県",
          "value": "aichi"
        },
        {
          "label": "静岡県",
          "value": "shizuoka"
        }
      ]
    }
  },
  "path": "/:pref?/:city?",
  "radar": [
    {
      "source": [
        "canaeru.usen.com/bukken/:pref/search/:city",
        "canaeru.usen.com/bukken/:pref/search"
      ],
      "target": "/:pref"
    }
  ],
  "topFeeds": [],
  "url": "canaeru.usen.com"
}
```
