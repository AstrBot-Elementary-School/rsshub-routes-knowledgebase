# 财联社 - 电报

## Coverage
`index-only`

## Route
- Namespace: `cls`
- Namespace Name: `财联社`
- Route Path: `/cls/telegraph/:category?`
- Route Name: `电报`
- Example: `/cls/telegraph`
- URL: `cls.cn/telegraph`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `nczitzk`
- Source Location: `telegraph.tsx`
- Source Module: `_None_`

## Description
| 看盘  | 公司         | 加红 | 提醒   | 基金 | 港美股 |
| ----- | ------------ | ---- | ------ | ---- | ------ |
| watch | announcement | red  | remind | fund | hk\_us |

## Parameters
- `category`: 分类，见下表，默认为全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cls.cn/telegraph`
  - `cls.cn/`
- `target`: `/telegraph`

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "description": "| 看盘  | 公司         | 加红 | 提醒   | 基金 | 港美股 |\n| ----- | ------------ | ---- | ------ | ---- | ------ |\n| watch | announcement | red  | remind | fund | hk\\_us |",
  "example": "/cls/telegraph",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1496,
  "location": "telegraph.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "电报",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/telegraph/:category?",
  "radar": [
    {
      "source": [
        "cls.cn/telegraph",
        "cls.cn/"
      ],
      "target": "/telegraph"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "财联社 - 电报 - Powered by RSSHub",
      "errorAt": "2026-09-02T03:43:20.840Z",
      "errorMessage": "Failed query: select \"id\", \"guid\", \"media\" from \"entries\" \"entries\" where \"entries\".\"feed_id\" = $1\nparams: 53366652701156363",
      "id": "53366652701156363",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cls.cn/telegraph",
      "title": "财联社 - 电报",
      "type": "feed",
      "url": "rsshub://cls/telegraph"
    },
    {
      "description": "财联社 - 电报 - 加红 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59187056197799936",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.cls.cn/telegraph",
      "title": "财联社 - 电报 - 加红",
      "type": "feed",
      "url": "rsshub://cls/telegraph/red"
    }
  ],
  "url": "cls.cn/telegraph"
}
```
