# Japan Local Government - 大阪市 食品営業許可 新規

## Coverage
`index-only`

## Route
- Namespace: `lg`
- Namespace Name: `Japan Local Government`
- Route Path: `/lg/osaka/food-permit`
- Route Name: `大阪市 食品営業許可 新規`
- Example: `/lg/osaka/food-permit`
- URL: `www.city.osaka.lg.jp`
- Language: `_None_`
- Categories: `government`
- Maintainers: `pseudoyu`
- Source Location: `osaka/food-permit.ts`
- Source Module: `_None_`

## Description
Newest food business permits (食品営業許可) in 大阪市，from the CC BY 4.0 [食品営業許可施設一覧 CSV](https://www.city.osaka.lg.jp/kenko/page/0000575579.html) — a quarterly snapshot of all valid permits with 緯度経度.

The dataset has no permit date, only 許可満了日，so items have no `pubDate`; they are ordered by 指令番号 (`大 保食第<年度>-<連番>号`), newest first, and only 申請区分 = 新規 rows are included. `_extra` holds `source`, `ward`, `permit_no`, `name`, `address`, `permit_date` (always `null`), `expires_at` (許可満了日), `business_type`, `lat`, `lon` and the publisher's original columns in `raw`. 大阪市 publishes no 町字，初回許可日 or 廃業日，so `town`, `first_permit_date` and `closed_date` are always `null` here.

| Query   | Description                | Default |
| ------- | -------------------------- | ------- |
| `limit` | Number of permits, max 500 | 100     |

## Parameters
_None_


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
    "government"
  ],
  "description": "Newest food business permits (食品営業許可) in 大阪市，from the CC BY 4.0 [食品営業許可施設一覧 CSV](https://www.city.osaka.lg.jp/kenko/page/0000575579.html) — a quarterly snapshot of all valid permits with 緯度経度.\n\nThe dataset has no permit date, only 許可満了日，so items have no `pubDate`; they are ordered by 指令番号 (`大 保食第<年度>-<連番>号`), newest first, and only 申請区分 = 新規 rows are included. `_extra` holds `source`, `ward`, `permit_no`, `name`, `address`, `permit_date` (always `null`), `expires_at` (許可満了日), `business_type`, `lat`, `lon` and the publisher's original columns in `raw`. 大阪市 publishes no 町字，初回許可日 or 廃業日，so `town`, `first_permit_date` and `closed_date` are always `null` here.\n\n| Query   | Description                | Default |\n| ------- | -------------------------- | ------- |\n| `limit` | Number of permits, max 500 | 100     |",
  "example": "/lg/osaka/food-permit",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": false
  },
  "heat": 0,
  "location": "osaka/food-permit.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "大阪市 食品営業許可 新規",
  "path": "/osaka/food-permit",
  "topFeeds": [],
  "url": "www.city.osaka.lg.jp"
}
```
