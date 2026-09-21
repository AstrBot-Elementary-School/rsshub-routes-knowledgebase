# Toei Transportation - 都営地下鉄 各駅乗降人員

## Coverage
`index-only`

## Route
- Namespace: `toei`
- Namespace Name: `Toei Transportation`
- Route Path: `/toei/ridership`
- Route Name: `都営地下鉄 各駅乗降人員`
- Example: `/toei/ridership`
- URL: `www.kotsu.metro.tokyo.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `ridership.ts`
- Source Module: `_None_`

## Description
Annual 各駅乗降人員 (one-day average of boarding + alighting passengers) for every 都営地下鉄 station, read from the Tokyo open-data catalog dataset [地下鉄関連情報 各駅乗降人員一覧](https://catalog.data.metro.tokyo.lg.jp/dataset/t000018d0000000030) (CC BY 4.0, one Shift_JIS CSV per line) — the operator's own [各駅乗降人員一覧](https://www.kotsu.metro.tokyo.jp/subway/kanren/passengers.html) page carries the same figures behind a browser challenge. One item per station and line (stations shared by two lines appear once per line with that line's figures); `_extra` follows the shared ridership shape with `daily_average` = 乗車 + 降車 and `measure: 'boarding_alighting'`. Only the current fiscal year is published and the files are overwritten in place; `pubDate` is the resource's last-modified date. Credit: 地下鉄関連情報 各駅乗降人員一覧、東京都・東京都交通局、CC BY 4.0.

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.kotsu.metro.tokyo.jp/subway/kanren/passengers.html`
  - `catalog.data.metro.tokyo.lg.jp/dataset/t000018d0000000030`
- `target`: `/ridership`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Annual 各駅乗降人員 (one-day average of boarding + alighting passengers) for every 都営地下鉄 station, read from the Tokyo open-data catalog dataset [地下鉄関連情報 各駅乗降人員一覧](https://catalog.data.metro.tokyo.lg.jp/dataset/t000018d0000000030) (CC BY 4.0, one Shift_JIS CSV per line) — the operator's own [各駅乗降人員一覧](https://www.kotsu.metro.tokyo.jp/subway/kanren/passengers.html) page carries the same figures behind a browser challenge. One item per station and line (stations shared by two lines appear once per line with that line's figures); `_extra` follows the shared ridership shape with `daily_average` = 乗車 + 降車 and `measure: 'boarding_alighting'`. Only the current fiscal year is published and the files are overwritten in place; `pubDate` is the resource's last-modified date. Credit: 地下鉄関連情報 各駅乗降人員一覧、東京都・東京都交通局、CC BY 4.0.",
  "example": "/toei/ridership",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "ridership.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "都営地下鉄 各駅乗降人員",
  "parameters": {},
  "path": "/ridership",
  "radar": [
    {
      "source": [
        "www.kotsu.metro.tokyo.jp/subway/kanren/passengers.html",
        "catalog.data.metro.tokyo.lg.jp/dataset/t000018d0000000030"
      ],
      "target": "/ridership"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "www.kotsu.metro.tokyo.jp"
}
```
