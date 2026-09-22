# JavDB - 搜索

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/javdb/search/:keyword?/:filter?/:sort?`
- Route Name: `搜索`
- Example: `/javdb/search/巨乳`
- URL: `javdb.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
过滤

| 全部 | 占位 | 可播放   | 單體作品 | 演員  | 片商  | 導演     | 系列   | 番號 | 可下載   | 字幕  | 預覽圖  |
| ---- | ---- | -------- | -------- | ----- | ----- | -------- | ------ | ---- | -------- | ----- | ------- |
|      | none | playable | single   | actor | maker | director | series | code | download | cnsub | preview |

排序

| 按相关度排序 | 按发布时间排序 |
| ------------ | -------------- |
| 0            | 1              |

## Parameters
- `keyword`: 关键字，默认为空
- `filter`: 过滤，见下表，默认为 `可播放`
- `sort`: 排序，见下表，默认为 `按相关度排序`


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
  "description": "过滤\n\n| 全部 | 占位 | 可播放   | 單體作品 | 演員  | 片商  | 導演     | 系列   | 番號 | 可下載   | 字幕  | 預覽圖  |\n| ---- | ---- | -------- | -------- | ----- | ----- | -------- | ------ | ---- | -------- | ----- | ------- |\n|      | none | playable | single   | actor | maker | director | series | code | download | cnsub | preview |\n\n排序\n\n| 按相关度排序 | 按发布时间排序 |\n| ------------ | -------------- |\n| 0            | 1              |",
  "example": "/javdb/search/巨乳",
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
  "heat": 226,
  "location": "search.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "搜索",
  "parameters": {
    "filter": "过滤，见下表，默认为 `可播放`",
    "keyword": "关键字，默认为空",
    "sort": "排序，见下表，默认为 `按相关度排序`"
  },
  "path": "/search/:keyword?/:filter?/:sort?",
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
      "description": "關鍵字 按相关度排序 搜索結果 - JavDB - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67212739482473472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/search?q=&sb=0",
      "title": "關鍵字 按相关度排序 搜索結果 - JavDB",
      "type": "feed",
      "url": "rsshub://javdb/search"
    },
    {
      "description": "關鍵字 巨乳 按相关度排序 搜索結果 - JavDB - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62403400668747776",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/search?q=%E5%B7%A8%E4%B9%B3&sb=0",
      "title": "關鍵字 巨乳 按相关度排序 搜索結果 - JavDB",
      "type": "feed",
      "url": "rsshub://javdb/search/%E5%B7%A8%E4%B9%B3"
    }
  ],
  "url": "javdb.com/"
}
```
