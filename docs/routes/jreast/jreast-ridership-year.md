# JR East - 各駅の乗車人員

## Coverage
`index-only`

## Route
- Namespace: `jreast`
- Namespace Name: `JR East`
- Route Path: `/jreast/ridership/:year?`
- Route Name: `各駅の乗車人員`
- Example: `/jreast/ridership`
- URL: `www.jreast.co.jp`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `ridership.ts`
- Source Module: `_None_`

## Description
Annual 各駅の乗車人員 (one-day average of boarding passengers) for every JR東日本 station, from [各駅の乗車人員](https://www.jreast.co.jp/company/data/passenger/) (ベスト100 plus the 101位以下 pages). One item per station and fiscal year; `_extra` follows the shared ridership shape with `measure: 'boarding'` — JR東日本 counts 乗車 only, so the figures are not comparable with the 乗降 figures of other operators. `yoy_pct` is normalised to a % change (the site prints a ratio such as 102.5 from FY2023 on). The operator does not publish a release date, so items have no `pubDate`.

::: warning
The site's [ご利用にあたって](https://www.jreast.co.jp/site/rules.html) states: 「当サイト上に掲載されている全ての写真、社名ロゴ、画像、文章等のデータ等の利用については、複製・転用・転載・電磁的加工・送信・頒布・二次的使用・その他これらに類する全ての行為も含め、一切お断りいたします。」 Use the figures accordingly.
:::

## Parameters
- `year`: {"description": "Fiscal year (`2019` … latest); omit for the latest year"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.jreast.co.jp/company/data/passenger/`
  - `www.jreast.co.jp/passenger/`
- `target`: `/ridership`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "Annual 各駅の乗車人員 (one-day average of boarding passengers) for every JR東日本 station, from [各駅の乗車人員](https://www.jreast.co.jp/company/data/passenger/) (ベスト100 plus the 101位以下 pages). One item per station and fiscal year; `_extra` follows the shared ridership shape with `measure: 'boarding'` — JR東日本 counts 乗車 only, so the figures are not comparable with the 乗降 figures of other operators. `yoy_pct` is normalised to a % change (the site prints a ratio such as 102.5 from FY2023 on). The operator does not publish a release date, so items have no `pubDate`.\n\n::: warning\nThe site's [ご利用にあたって](https://www.jreast.co.jp/site/rules.html) states: 「当サイト上に掲載されている全ての写真、社名ロゴ、画像、文章等のデータ等の利用については、複製・転用・転載・電磁的加工・送信・頒布・二次的使用・その他これらに類する全ての行為も含め、一切お断りいたします。」 Use the figures accordingly.\n:::",
  "example": "/jreast/ridership",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "ridership.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "各駅の乗車人員",
  "parameters": {
    "year": {
      "description": "Fiscal year (`2019` … latest); omit for the latest year"
    }
  },
  "path": "/ridership/:year?",
  "radar": [
    {
      "source": [
        "www.jreast.co.jp/company/data/passenger/",
        "www.jreast.co.jp/passenger/"
      ],
      "target": "/ridership"
    }
  ],
  "topFeeds": [],
  "url": "www.jreast.co.jp"
}
```
