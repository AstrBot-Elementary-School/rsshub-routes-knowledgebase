# Japan Local Government - 東京都統計年鑑 駅別乗降車人員

## Coverage
`index-only`

## Route
- Namespace: `lg`
- Namespace Name: `Japan Local Government`
- Route Path: `/lg/tokyo/rail-ridership/:table?`
- Route Name: `東京都統計年鑑 駅別乗降車人員`
- Example: `/lg/tokyo/rail-ridership`
- URL: `catalog.data.metro.tokyo.lg.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `tokyo/rail-ridership.ts`
- Source Module: `_None_`

## Description
Per-station yearly ridership for Tokyo's private railways and subways, from the [東京都統計年鑑 運輸・観光](https://catalog.data.metro.tokyo.lg.jp/dataset/t000003d2000001150) (CC BY 4.0). One item per station and fiscal year.

This is the only permissively licensed source covering ゆりかもめ, りんかい線 (東京臨海高速鉄道) and つくばエクスプレス (首都圏新都市鉄道) — their own sites either publish no per-station table or forbid reuse.

Read the figures carefully:

- They are **one-year totals in 千人**, not the 一日平均 in 人/日 that operators publish. `_extra` carries `annual_total` with `unit: '千人/年'` and leaves `daily_average` null; the route never converts between the two.
- The table gives 乗車人員 and 降車人員 in separate columns. The item carries 乗車 (`measure: 'boarding'`) and leaves 降車 verbatim in `raw`, rather than summing them.
- Only stations **within 東京都** are listed, so a line is truncated at the prefecture border. The publisher's `マーク` column (kept in `raw`) marks 「◎ 同一会社内の乗換え駅」 and 「※ 区部にある駅 (線)」.
- Figures 「同一会社内の乗り継ぎは除く」 (exclude transfers within the same company).

The table number changes between editions (私鉄 was 4-12 in 令和6年 but 4-13 in 令和5年), so the route resolves the current edition and table through the catalog API by name rather than a fixed URL.

Attribution required by the licence: 出典：東京都統計年鑑（東京都総務局統計部）.

## Parameters
- `table`: {"description": "Which yearbook table to read; defaults to 私鉄", "options": [{"label": "私鉄の駅別乗降車人員", "value": "private"}, {"label": "地下鉄の駅別乗降車人員", "value": "subway"}]}


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
    "other"
  ],
  "description": "Per-station yearly ridership for Tokyo's private railways and subways, from the [東京都統計年鑑 運輸・観光](https://catalog.data.metro.tokyo.lg.jp/dataset/t000003d2000001150) (CC BY 4.0). One item per station and fiscal year.\n\nThis is the only permissively licensed source covering ゆりかもめ, りんかい線 (東京臨海高速鉄道) and つくばエクスプレス (首都圏新都市鉄道) — their own sites either publish no per-station table or forbid reuse.\n\nRead the figures carefully:\n\n- They are **one-year totals in 千人**, not the 一日平均 in 人/日 that operators publish. `_extra` carries `annual_total` with `unit: '千人/年'` and leaves `daily_average` null; the route never converts between the two.\n- The table gives 乗車人員 and 降車人員 in separate columns. The item carries 乗車 (`measure: 'boarding'`) and leaves 降車 verbatim in `raw`, rather than summing them.\n- Only stations **within 東京都** are listed, so a line is truncated at the prefecture border. The publisher's `マーク` column (kept in `raw`) marks 「◎ 同一会社内の乗換え駅」 and 「※ 区部にある駅 (線)」.\n- Figures 「同一会社内の乗り継ぎは除く」 (exclude transfers within the same company).\n\nThe table number changes between editions (私鉄 was 4-12 in 令和6年 but 4-13 in 令和5年), so the route resolves the current edition and table through the catalog API by name rather than a fixed URL.\n\nAttribution required by the licence: 出典：東京都統計年鑑（東京都総務局統計部）.",
  "example": "/lg/tokyo/rail-ridership",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": false
  },
  "heat": 0,
  "location": "tokyo/rail-ridership.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "東京都統計年鑑 駅別乗降車人員",
  "parameters": {
    "table": {
      "description": "Which yearbook table to read; defaults to 私鉄",
      "options": [
        {
          "label": "私鉄の駅別乗降車人員",
          "value": "private"
        },
        {
          "label": "地下鉄の駅別乗降車人員",
          "value": "subway"
        }
      ]
    }
  },
  "path": "/tokyo/rail-ridership/:table?",
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "catalog.data.metro.tokyo.lg.jp"
}
```
