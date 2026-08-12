# JavDB - 系列

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/javdb/series/:id/:filter?`
- Route Name: `系列`
- Example: `/javdb/series/1NW`
- URL: `javdb.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `series.ts`
- Source Module: `_None_`

## Description
| 全部 | 可播放   | 單體作品 | 可下載   | 字幕  | 預覽圖  |
| ---- | -------- | -------- | -------- | ----- | ------- |
|      | playable | single   | download | cnsub | preview |

所有系列编号参见 [系列庫](https://javdb.com/series)

## Parameters
- `id`: 编号，可在系列页 URL 中找到
- `filter`: 过滤，见下表，默认为 `全部`


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
    "multimedia"
  ],
  "description": "| 全部 | 可播放   | 單體作品 | 可下載   | 字幕  | 預覽圖  |\n| ---- | -------- | -------- | -------- | ----- | ------- |\n|      | playable | single   | download | cnsub | preview |\n\n所有系列编号参见 [系列庫](https://javdb.com/series)",
  "example": "/javdb/series/1NW",
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
  "heat": 201,
  "location": "series.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "系列",
  "parameters": {
    "filter": "过滤，见下表，默认为 `全部`",
    "id": "编号，可在系列页 URL 中找到"
  },
  "path": "/series/:id/:filter?",
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
      "description": "中出し 射精執行官 - JavDB - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84865535466264576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/series/3aZz",
      "title": "中出し 射精執行官 - JavDB",
      "type": "feed",
      "url": "rsshub://javdb/series/3aZz"
    },
    {
      "description": "絶対忠実秘書 - JavDB - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "85160035655452672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/series/ZO0X",
      "title": "絶対忠実秘書 - JavDB",
      "type": "feed",
      "url": "rsshub://javdb/series/ZO0X"
    }
  ],
  "url": "javdb.com/"
}
```
