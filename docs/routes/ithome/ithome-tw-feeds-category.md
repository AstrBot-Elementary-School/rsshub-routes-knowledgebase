# iThome 台灣 - Feeds

## Coverage
`index-only`

## Route
- Namespace: `ithome`
- Namespace Name: `iThome 台灣`
- Route Path: `/ithome/tw/feeds/:category`
- Route Name: `Feeds`
- Example: `/ithome/tw/feeds/news`
- URL: `ithome.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `miles170`
- Source Location: `tw/feeds.ts`
- Source Module: `_None_`

## Description
| 新聞 | AI       | Cloud | DevOps | 資安     |
| ---- | -------- | ----- | ------ | -------- |
| news | big-data | cloud | devops | security |

## Parameters
- `category`: 類別


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
  - `www.ithome.com.tw/:category`
  - `www.ithome.com.tw/:category/feeds`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 新聞 | AI       | Cloud | DevOps | 資安     |\n| ---- | -------- | ----- | ------ | -------- |\n| news | big-data | cloud | devops | security |",
  "example": "/ithome/tw/feeds/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 94,
  "location": "tw/feeds.ts",
  "maintainers": [
    "miles170"
  ],
  "name": "Feeds",
  "parameters": {
    "category": "類別"
  },
  "path": "/tw/feeds/:category",
  "radar": [
    {
      "source": [
        "www.ithome.com.tw/:category",
        "www.ithome.com.tw/:category/feeds"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "iThome Online 是臺灣第一個網路原生報，提供IT產業即時新聞、企業IT產品報導與測試、技術專題、IT應用報導、IT書訊，以及面向豐富的名家專欄。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59766252606947328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ithome.com.tw/news/feeds",
      "title": "新聞 | iThome",
      "type": "feed",
      "url": "rsshub://ithome/tw/feeds/news"
    },
    {
      "description": "iThome Online 是臺灣第一個網路原生報，提供IT產業即時新聞、企業IT產品報導與測試、技術專題、IT應用報導、IT書訊，以及面向豐富的名家專欄。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74695455133844486",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ithome.com.tw/security/feeds",
      "title": "資安 | iThome",
      "type": "feed",
      "url": "rsshub://ithome/tw/feeds/security"
    }
  ]
}
```
