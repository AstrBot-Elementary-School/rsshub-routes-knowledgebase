# Bukenavi - 新着物件

## Coverage
`index-only`

## Route
- Namespace: `bukenavi`
- Namespace Name: `Bukenavi`
- Route Path: `/bukenavi/object/:region?/:pref?/:city?`
- Route Name: `新着物件`
- Example: `/bukenavi/object/kanto/tokyo`
- URL: `bukenavi.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `object.ts`
- Source Module: `_None_`

## Description
New 居抜き listings on ぶけなび that are currently 募集中，newest first (first page, 10 listings) — for a region, a prefecture, or one 市区町村 when `city` is given. Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，前業態，業種制限，…) parsed from the list and detail pages; unknown values are `null`. The site does not publish listing dates, so items have no `pubDate`.

**With an account it also reads the 会員限定 fields.** Set `BUKENAVI_EMAIL` and `BUKENAVI_PASSWORD` and 住所 comes through to the 番地 (`東京都新宿区歌舞伎町 2-9-10`), plus 物件名，保証金・敷金，礼金，償却，共益費，造作譲渡金額，契約年数，座席 and an explicit 居抜き / スケルトン. Both variables are optional and the route is fully usable without them — it stays a guest and leaves those `null`.

**Without an account the exact location is still in `raw.lat` / `raw.lng`, not in the address.** ぶけなび truncates 住所 to the 町 for guests (「東京都新宿区歌舞伎町 ※詳細はお問い合わせください（住所詳細は会員限定）」), but the page's own map pin does not: `initMap()` is called with the listing's coordinates, and five 歌舞伎町 listings carry five different pairs spread over roughly 265m × 440m, so these are per-property positions rather than a geocode of the town. They are finer than the 丁目 the address withholds, and no account is needed for them.

`city` is a 5-digit JIS X 0402 code and the site pairs it with the prefecture, so both are required — `/bukenavi/object/kanto/kanagawa/14104` is 横浜市中区. A code that does not belong to `pref` is rejected rather than sent on.

Note that `bukenavi.jp/{region}/area/{日本語}` pages are SEO landing pages carrying no listings; the 市区町村 filter is the `city[]` parameter on the list endpoint, which is what this route uses.

## Parameters
- `region`: {"default": "kanto", "description": "Region", "options": [{"label": "関東", "value": "kanto"}, {"label": "関西", "value": "kansai"}, {"label": "東海", "value": "tokai"}]}
- `pref`: Prefecture slug (tokyo, kanagawa, saitama, chiba, osaka, kyoto, hyogo, aichi) or two-digit JIS X 0401 code; omit for the whole region
- `city`: {"description": "Optional 市区町村, as a 5-digit JIS X 0402 code (横浜市中区 `14104`, 新宿区 `13104`). Requires `pref` and must belong to it; omit for the whole prefecture."}


## Features
- `requireConfig`: [{"description": "ぶけなび account e-mail. Optional — without it the route reads the public view.", "name": "BUKENAVI_EMAIL", "optional": true}, {"description": "ぶけなび account password. Optional — without it the route reads the public view.", "name": "BUKENAVI_PASSWORD", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `bukenavi.jp/:region/object/list`
  - `bukenavi.jp/:region`
- `target`: `/object/:region`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "New 居抜き listings on ぶけなび that are currently 募集中，newest first (first page, 10 listings) — for a region, a prefecture, or one 市区町村 when `city` is given. Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，前業態，業種制限，…) parsed from the list and detail pages; unknown values are `null`. The site does not publish listing dates, so items have no `pubDate`.\n\n**With an account it also reads the 会員限定 fields.** Set `BUKENAVI_EMAIL` and `BUKENAVI_PASSWORD` and 住所 comes through to the 番地 (`東京都新宿区歌舞伎町 2-9-10`), plus 物件名，保証金・敷金，礼金，償却，共益費，造作譲渡金額，契約年数，座席 and an explicit 居抜き / スケルトン. Both variables are optional and the route is fully usable without them — it stays a guest and leaves those `null`.\n\n**Without an account the exact location is still in `raw.lat` / `raw.lng`, not in the address.** ぶけなび truncates 住所 to the 町 for guests (「東京都新宿区歌舞伎町 ※詳細はお問い合わせください（住所詳細は会員限定）」), but the page's own map pin does not: `initMap()` is called with the listing's coordinates, and five 歌舞伎町 listings carry five different pairs spread over roughly 265m × 440m, so these are per-property positions rather than a geocode of the town. They are finer than the 丁目 the address withholds, and no account is needed for them.\n\n`city` is a 5-digit JIS X 0402 code and the site pairs it with the prefecture, so both are required — `/bukenavi/object/kanto/kanagawa/14104` is 横浜市中区. A code that does not belong to `pref` is rejected rather than sent on.\n\nNote that `bukenavi.jp/{region}/area/{日本語}` pages are SEO landing pages carrying no listings; the 市区町村 filter is the `city[]` parameter on the list endpoint, which is what this route uses.",
  "example": "/bukenavi/object/kanto/tokyo",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "ぶけなび account e-mail. Optional — without it the route reads the public view.",
        "name": "BUKENAVI_EMAIL",
        "optional": true
      },
      {
        "description": "ぶけなび account password. Optional — without it the route reads the public view.",
        "name": "BUKENAVI_PASSWORD",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "object.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "新着物件",
  "parameters": {
    "city": {
      "description": "Optional 市区町村, as a 5-digit JIS X 0402 code (横浜市中区 `14104`, 新宿区 `13104`). Requires `pref` and must belong to it; omit for the whole prefecture."
    },
    "pref": "Prefecture slug (tokyo, kanagawa, saitama, chiba, osaka, kyoto, hyogo, aichi) or two-digit JIS X 0401 code; omit for the whole region",
    "region": {
      "default": "kanto",
      "description": "Region",
      "options": [
        {
          "label": "関東",
          "value": "kanto"
        },
        {
          "label": "関西",
          "value": "kansai"
        },
        {
          "label": "東海",
          "value": "tokai"
        }
      ]
    }
  },
  "path": "/object/:region?/:pref?/:city?",
  "radar": [
    {
      "source": [
        "bukenavi.jp/:region/object/list",
        "bukenavi.jp/:region"
      ],
      "target": "/object/:region"
    }
  ],
  "topFeeds": [],
  "url": "bukenavi.jp"
}
```
