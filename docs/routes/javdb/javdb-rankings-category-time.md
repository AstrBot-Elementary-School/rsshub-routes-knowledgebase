# JavDB - 排行榜

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/javdb/rankings/:category?/:time?`
- Route Name: `排行榜`
- Example: `/javdb/rankings`
- URL: `javdb.com/`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `nczitzk`
- Source Location: `rankings.ts`
- Source Module: `_None_`

## Description
分类

| 有碼     | 無碼       | 歐美    |
| -------- | ---------- | ------- |
| censored | uncensored | western |

时间

| 日榜  | 週榜   | 月榜    |
| ----- | ------ | ------- |
| daily | weekly | monthly |

## Parameters
- `category`: 分类，见下表，默认为 `有碼`
- `time`: 时间，见下表，默认为 `日榜`


## Features
- `requireConfig`: [{"description": "JavDB登陆后的session值，可在控制台的cookie下查找 `_jdb_session` 的值，即可获取", "name": "JAVDB_SESSION", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `javdb.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "multimedia",
    "popular"
  ],
  "description": "分类\n\n| 有碼     | 無碼       | 歐美    |\n| -------- | ---------- | ------- |\n| censored | uncensored | western |\n\n时间\n\n| 日榜  | 週榜   | 月榜    |\n| ----- | ------ | ------- |\n| daily | weekly | monthly |",
  "example": "/javdb/rankings",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "JavDB登陆后的session值，可在控制台的cookie下查找 `_jdb_session` 的值，即可获取",
        "name": "JAVDB_SESSION",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2427,
  "location": "rankings.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "排行榜",
  "parameters": {
    "category": "分类，见下表，默认为 `有碼`",
    "time": "时间，见下表，默认为 `日榜`"
  },
  "path": "/rankings/:category?/:time?",
  "radar": [
    {
      "source": [
        "javdb.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "有碼排行 - 日排行 - JavDB - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41696949079348224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/rankings/movies?p=daily&t=censored",
      "title": "有碼排行 - 日排行 - JavDB",
      "type": "feed",
      "url": "rsshub://javdb/rankings"
    },
    {
      "description": "有碼排行 - 月排行 - JavDB - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57074574176806917",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/rankings/movies?p=monthly&t=censored",
      "title": "有碼排行 - 月排行 - JavDB",
      "type": "feed",
      "url": "rsshub://javdb/rankings/censored/monthly"
    }
  ],
  "url": "javdb.com/"
}
```
