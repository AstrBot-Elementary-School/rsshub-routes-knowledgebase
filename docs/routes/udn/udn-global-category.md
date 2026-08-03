# 聯合新聞網 - 轉角國際 - 首頁

## Coverage
`index-only`

## Route
- Namespace: `udn`
- Namespace Name: `聯合新聞網`
- Route Path: `/udn/global/:category?`
- Route Name: `轉角國際 - 首頁`
- Example: `/udn/global`
- URL: `udn.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `global/index.ts`
- Source Module: `_None_`

## Description
| 首頁 | 編輯精選 | 熱門文章 |
| ---- | -------- | -------- |
|      | editor   | hot      |

## Parameters
- `category`: 分类，见下表，默认为首頁


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
  - `global.udn.com/global_vision/index`
  - `global.udn.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 首頁 | 編輯精選 | 熱門文章 |\n| ---- | -------- | -------- |\n|      | editor   | hot      |",
  "example": "/udn/global",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 100,
  "location": "global/index.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "轉角國際 - 首頁",
  "parameters": {
    "category": "分类，见下表，默认为首頁"
  },
  "path": "/global/:category?",
  "radar": [
    {
      "source": [
        "global.udn.com/global_vision/index",
        "global.udn.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "轉角國際 udn Global - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41373653871256597",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://global.udn.com/global_vision/index",
      "title": "轉角國際 udn Global",
      "type": "feed",
      "url": "rsshub://udn/global"
    },
    {
      "description": "轉角國際 udn Global - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "157947335946852352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://global.udn.com/global_vision/index",
      "title": "轉角國際 udn Global",
      "type": "feed",
      "url": "rsshub://udn/global/hot"
    }
  ]
}
```
