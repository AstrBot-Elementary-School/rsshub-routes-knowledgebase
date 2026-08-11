# JavDB - 演員

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/javdb/actors/:id/:filter?`
- Route Name: `演員`
- Example: `/javdb/actors/R2Vg`
- URL: `javdb.com/`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `nczitzk`
- Source Location: `actors.ts`
- Source Module: `_None_`

## Description
| 全部 | 可播放 | 單體作品 | 可下載 | 含字幕 |
| ---- | ------ | -------- | ------ | ------ |
|      | p      | s        | d      | c      |

所有演员编号参见 [演員庫](https://javdb.com/actors)

可用 addon\_tags 参数添加额外的过滤 tag，可从网页 url 中获取，例如 `/javdb/actors/R2Vg?addon_tags=212,18` 可筛选 `VR` 和 `中出`。

## Parameters
- `id`: 编号，可在演员页 URL 中找到
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
    "multimedia",
    "popular"
  ],
  "description": "| 全部 | 可播放 | 單體作品 | 可下載 | 含字幕 |\n| ---- | ------ | -------- | ------ | ------ |\n|      | p      | s        | d      | c      |\n\n所有演员编号参见 [演員庫](https://javdb.com/actors)\n\n可用 addon\\_tags 参数添加额外的过滤 tag，可从网页 url 中获取，例如 `/javdb/actors/R2Vg?addon_tags=212,18` 可筛选 `VR` 和 `中出`。",
  "example": "/javdb/actors/R2Vg",
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
  "heat": 4869,
  "location": "actors.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "演員",
  "parameters": {
    "filter": "过滤，见下表，默认为 `全部`",
    "id": "编号，可在演员页 URL 中找到"
  },
  "path": "/actors/:id/:filter?",
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
      "description": "桃乃木香奈 - JavDB - Powered by RSSHub",
      "errorAt": "2026-08-06T16:29:20.614Z",
      "errorMessage": "Failed to fetch\n[GET] \"https://javdb.com/actors/0dKX\": 403 Forbidden\nAuthentication failed. Access denied.\n/javdb/actors/0dKX\n[GET] \"https://javdb.com/actors/0dKX\": 403 Forbidden\nFailed to fetch\n[GET] \"https://javdb.com/actors/0dKX\": 403 Forbidden\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "58137945200229376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/actors/0dKX",
      "title": "桃乃木香奈 - JavDB",
      "type": "feed",
      "url": "rsshub://javdb/actors/0dKX"
    },
    {
      "description": "河北彩花 - JavDB - Powered by RSSHub",
      "errorAt": "2026-08-06T17:57:02.528Z",
      "errorMessage": "Failed to fetch\nFailed to fetch\nAuthentication failed. Access denied.\n/javdb/actors/EvkJ\nFailed to fetch\n[GET] \"https://javdb.com/actors/EvkJ\": 403 Forbidden\n[GET] \"https://javdb.com/actors/EvkJ\": 403 Forbidden\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "59231069957378048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/actors/EvkJ",
      "title": "河北彩花 - JavDB",
      "type": "feed",
      "url": "rsshub://javdb/actors/EvkJ"
    }
  ],
  "url": "javdb.com/"
}
```
