# Sub HD - 字幕

## Coverage
`index-only`

## Route
- Namespace: `subhd`
- Namespace Name: `Sub HD`
- Route Path: `/subhd/sub/:category?`
- Route Name: `字幕`
- Example: `/subhd/sub/new`
- URL: `subhd.tv`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `laampui, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 最新字幕 | 热门字幕 | 剧集字幕 | 电影字幕 |
| -------- | -------- | -------- | -------- |
| new      | top      | tv       | movie    |

## Parameters
- `category`: 分类，见下表，默认为最新


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `subhd.tv/sub/:category`
  - `subhd.tv/`
- `target`: `/sub/:category?`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| 最新字幕 | 热门字幕 | 剧集字幕 | 电影字幕 |\n| -------- | -------- | -------- | -------- |\n| new      | top      | tv       | movie    |",
  "example": "/subhd/sub/new",
  "heat": 17,
  "location": "index.ts",
  "maintainers": [
    "laampui",
    "nczitzk"
  ],
  "name": "字幕",
  "parameters": {
    "category": "分类，见下表，默认为最新"
  },
  "path": "/sub/:category?",
  "radar": [
    {
      "source": [
        "subhd.tv/sub/:category",
        "subhd.tv/"
      ],
      "target": "/sub/:category?"
    }
  ],
  "topFeeds": [
    {
      "description": "最新字幕 分享交流下载字幕平台 - SubHD - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70777567210160142",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://subhd.tv/sub/new",
      "title": "最新字幕 分享交流下载字幕平台 - SubHD",
      "type": "feed",
      "url": "rsshub://subhd/sub/new"
    }
  ]
}
```
