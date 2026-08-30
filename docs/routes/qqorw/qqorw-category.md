# 早报网 - 每日早报

## Coverage
`index-only`

## Route
- Namespace: `qqorw`
- Namespace Name: `早报网`
- Route Path: `/qqorw/:category?`
- Route Name: `每日早报`
- Example: `/qqorw`
- URL: `qqorw.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 首页 | 每日早报 | 国际早报 | 生活冷知识 |
| ---- | -------- | -------- | ---------- |
|      | mrzb     | zbapp    | zbzzd      |

## Parameters
- `category`: 分类，见下表，默认为首页


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
  - `qqorw.cn/:category`
  - `qqorw.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 首页 | 每日早报 | 国际早报 | 生活冷知识 |\n| ---- | -------- | -------- | ---------- |\n|      | mrzb     | zbapp    | zbzzd      |",
  "example": "/qqorw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 41,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "每日早报",
  "parameters": {
    "category": "分类，见下表，默认为首页"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "qqorw.cn/:category",
        "qqorw.cn/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "每天更新15条简语早报和一条微语，国际早报，财经早报，早报软件，每天60秒足不出户了解天下事！ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66400977219680256",
      "image": "https://qqorw.cn/static/upload/2022/07/22/202207227737.png",
      "ownerUserId": null,
      "siteUrl": "https://qqorw.cn/",
      "title": "早报网",
      "type": "feed",
      "url": "rsshub://qqorw"
    },
    {
      "description": "每天更新15条简语早报和一条微语，国际早报，财经早报，早报软件，每天60秒足不出户了解天下事！ - Powered by RSSHub",
      "errorAt": "2025-11-02T13:44:08.846Z",
      "errorMessage": "[GET] \"https://qqorw.cn/zbzzd\": 403 Forbidden\n",
      "id": "69621932570571776",
      "image": "https://qqorw.cn/static/upload/2022/07/22/202207227737.png",
      "ownerUserId": null,
      "siteUrl": "https://qqorw.cn/zbzzd",
      "title": "早报网 - 生活冷知识",
      "type": "feed",
      "url": "rsshub://qqorw/zbzzd"
    }
  ]
}
```
