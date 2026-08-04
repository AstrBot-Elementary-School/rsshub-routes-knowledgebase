# JavDB - 番号

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/javdb/video_codes/:code/:filter?`
- Route Name: `番号`
- Example: `/javdb/video_codes/SIVR`
- URL: `javdb.com/`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `sgpublic`
- Source Location: `videocodes.ts`
- Source Module: `_None_`

## Description
| 全部 | 可播放   | 單體作品 | 可下載   | 字幕  | 預覽圖  |
| ---- | -------- | -------- | -------- | ----- | ------- |
|      | playable | single   | download | cnsub | preview |

## Parameters
- `id`: 番号前缀
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
  "description": "| 全部 | 可播放   | 單體作品 | 可下載   | 字幕  | 預覽圖  |\n| ---- | -------- | -------- | -------- | ----- | ------- |\n|      | playable | single   | download | cnsub | preview |",
  "example": "/javdb/video_codes/SIVR",
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
  "heat": 1585,
  "location": "videocodes.ts",
  "maintainers": [
    "sgpublic"
  ],
  "name": "番号",
  "parameters": {
    "filter": "过滤，见下表，默认为 `全部`",
    "id": "番号前缀"
  },
  "path": "/video_codes/:code/:filter?",
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
      "description": "SONE - JavDB - 可下載 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "96109559941147648",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/video_codes/SONE?f=download",
      "title": "SONE - JavDB - 可下載",
      "type": "feed",
      "url": "rsshub://javdb/video_codes/SONE/download"
    },
    {
      "description": "MIDV - JavDB - 可下載 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "96109559941147651",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/video_codes/MIDV?f=download",
      "title": "MIDV - JavDB - 可下載",
      "type": "feed",
      "url": "rsshub://javdb/video_codes/MIDV/download"
    }
  ],
  "url": "javdb.com/"
}
```
