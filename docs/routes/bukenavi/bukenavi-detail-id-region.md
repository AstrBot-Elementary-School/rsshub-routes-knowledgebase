# Bukenavi - 物件詳細

## Coverage
`index-only`

## Route
- Namespace: `bukenavi`
- Namespace Name: `Bukenavi`
- Route Path: `/bukenavi/detail/:id/:region?`
- Route Name: `物件詳細`
- Example: `/bukenavi/detail/54379`
- URL: `bukenavi.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `detail.ts`
- Source Module: `_None_`

## Description
One listing on ぶけなび，for following a single property rather than a whole area — a listing's 賃料 and availability change over its life.

It adds what the area route's cards omit: 乗降者数 for the nearest station, 構造，竣工年月，立地，間口，業種，不可業態，営業年数 and 特記事項，plus exact 面積 and 階数.

**With an account it also reads the 会員限定 fields.** Set `BUKENAVI_EMAIL` and `BUKENAVI_PASSWORD` and 住所 comes through to the 番地 (`東京都新宿区歌舞伎町 2-9-10`), plus 物件名，保証金・敷金，礼金，償却，共益費，造作譲渡金額，契約年数，座席，引渡し時期 and an explicit 居抜き / スケルトン. Both variables are optional and the route is fully usable without them — it simply stays a guest and leaves those `null`, which is the behaviour described below.

**Without an account the exact location is still in `raw.lat` / `raw.lng`, not in the address.** ぶけなび truncates 住所 to the 町 for guests and says so on the page — 「東京都新宿区歌舞伎町 ※詳細はお問い合わせください（住所詳細は会員限定）」 — so `address_hint` stops at the 町. The page's own map pin does not: `initMap()` is called with the listing's coordinates, and five 歌舞伎町 listings carry five different pairs spread over roughly 265m × 440m, so these are per-property positions rather than a geocode of the town. That makes them finer than the 丁目 the address withholds, and no account is needed for them. 敷金，礼金 and 造作 are absent from the guest view, and the site publishes no listing date, so those stay `null`.

## Parameters
- `id`: {"description": "The numeric 物件 id, i.e. the `54379` in `https://bukenavi.jp/kanto/object/54379`"}
- `region`: {"default": "kanto", "description": "Region the listing belongs to; defaults to `kanto`", "options": [{"label": "kanto", "value": "kanto"}, {"label": "kansai", "value": "kansai"}, {"label": "tokai", "value": "tokai"}, {"label": "kyushu", "value": "kyushu"}]}


## Features
- `requireConfig`: [{"description": "ぶけなび account e-mail. Optional — without it the route reads the public view.", "name": "BUKENAVI_EMAIL", "optional": true}, {"description": "ぶけなび account password. Optional — without it the route reads the public view.", "name": "BUKENAVI_PASSWORD", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `bukenavi.jp/:region/object/:id`
- `target`: `/detail/:id/:region`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "One listing on ぶけなび，for following a single property rather than a whole area — a listing's 賃料 and availability change over its life.\n\nIt adds what the area route's cards omit: 乗降者数 for the nearest station, 構造，竣工年月，立地，間口，業種，不可業態，営業年数 and 特記事項，plus exact 面積 and 階数.\n\n**With an account it also reads the 会員限定 fields.** Set `BUKENAVI_EMAIL` and `BUKENAVI_PASSWORD` and 住所 comes through to the 番地 (`東京都新宿区歌舞伎町 2-9-10`), plus 物件名，保証金・敷金，礼金，償却，共益費，造作譲渡金額，契約年数，座席，引渡し時期 and an explicit 居抜き / スケルトン. Both variables are optional and the route is fully usable without them — it simply stays a guest and leaves those `null`, which is the behaviour described below.\n\n**Without an account the exact location is still in `raw.lat` / `raw.lng`, not in the address.** ぶけなび truncates 住所 to the 町 for guests and says so on the page — 「東京都新宿区歌舞伎町 ※詳細はお問い合わせください（住所詳細は会員限定）」 — so `address_hint` stops at the 町. The page's own map pin does not: `initMap()` is called with the listing's coordinates, and five 歌舞伎町 listings carry five different pairs spread over roughly 265m × 440m, so these are per-property positions rather than a geocode of the town. That makes them finer than the 丁目 the address withholds, and no account is needed for them. 敷金，礼金 and 造作 are absent from the guest view, and the site publishes no listing date, so those stay `null`.",
  "example": "/bukenavi/detail/54379",
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
  "location": "detail.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "物件詳細",
  "parameters": {
    "id": {
      "description": "The numeric 物件 id, i.e. the `54379` in `https://bukenavi.jp/kanto/object/54379`"
    },
    "region": {
      "default": "kanto",
      "description": "Region the listing belongs to; defaults to `kanto`",
      "options": [
        {
          "label": "kanto",
          "value": "kanto"
        },
        {
          "label": "kansai",
          "value": "kansai"
        },
        {
          "label": "tokai",
          "value": "tokai"
        },
        {
          "label": "kyushu",
          "value": "kyushu"
        }
      ]
    }
  },
  "path": "/detail/:id/:region?",
  "radar": [
    {
      "source": [
        "bukenavi.jp/:region/object/:id"
      ],
      "target": "/detail/:id/:region"
    }
  ],
  "topFeeds": [],
  "url": "bukenavi.jp"
}
```
