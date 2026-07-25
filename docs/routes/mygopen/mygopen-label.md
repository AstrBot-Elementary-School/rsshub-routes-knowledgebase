# MyGoPen - 分類

## Coverage
`index-only`

## Route
- Namespace: `mygopen`
- Namespace Name: `MyGoPen`
- Route Path: `/mygopen/:label?`
- Route Name: `分類`
- Example: `/mygopen`
- URL: `mygopen.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 謠言 | 詐騙 | 真實資訊 | 教學 |
| ---- | ---- | -------- | ---- |

## Parameters
- `label`: 分類，见下表，默认为首页


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
  - `mygopen.com/search/label/:label`
  - `mygopen.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 謠言 | 詐騙 | 真實資訊 | 教學 |\n| ---- | ---- | -------- | ---- |",
  "example": "/mygopen",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 32,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分類",
  "parameters": {
    "label": "分類，见下表，默认为首页"
  },
  "path": "/:label?",
  "radar": [
    {
      "source": [
        "mygopen.com/search/label/:label",
        "mygopen.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "詐騙與謠言頻傳的年代，「MyGoPen｜這是假消息」提醒網路使用者隨時要用謹慎懷疑的態度面對網路上的消息。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57952509273994240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mygopen.com/",
      "title": "MyGoPen",
      "type": "feed",
      "url": "rsshub://mygopen"
    },
    {
      "description": "詐騙與謠言頻傳的年代，「MyGoPen｜這是假消息」提醒網路使用者隨時要用謹慎懷疑的態度面對網路上的消息。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "87469468353113088",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mygopen.com/search/label/%E7%9C%9F%E5%AF%A6%E8%B3%87%E8%A8%8A",
      "title": "MyGoPen: 真實資訊",
      "type": "feed",
      "url": "rsshub://mygopen/%E7%9C%9F%E5%AF%A6%E8%B3%87%E8%A8%8A"
    }
  ]
}
```
