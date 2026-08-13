# 有線新聞 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `i-cable`
- Namespace Name: `有線新聞`
- Route Path: `/i-cable/news/:category?`
- Route Name: `新聞`
- Example: `/i-cable/news`
- URL: `www.i-cable.com/`
- Language: `_None_`
- Categories: `traditional-media, popular`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
::: tip
分類只可用分類名稱，如：新聞資訊 / 港聞
:::

## Parameters
- `category`: 分類，默認為新聞資訊


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
  - `www.i-cable.com`
- `target`: `/news`
### Rule 2
- `source`:
  - `www.i-cable.com/category/:category`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media",
    "popular"
  ],
  "description": "::: tip\n分類只可用分類名稱，如：新聞資訊 / 港聞\n:::",
  "example": "/i-cable/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3567,
  "location": "news.tsx",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "name": "新聞",
  "parameters": {
    "category": "分類，默認為新聞資訊"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "www.i-cable.com"
      ],
      "target": "/news"
    },
    {
      "source": [
        "www.i-cable.com/category/:category"
      ],
      "target": "/news/:category"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "涵蓋突發消息、最新熱話、本地時事、國際要聞、兩岸大事、專題報導，以及《家國天下》、《議員同你傾》、《有理有得傾》等多個焦點資訊節目。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69780477411040256",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.i-cable.com/category/%e6%96%b0%e8%81%9e%e8%b3%87%e8%a8%8a",
      "title": "有線新聞 - 新聞資訊",
      "type": "feed",
      "url": "rsshub://i-cable/news"
    },
    {
      "description": "有線新聞 - 中國在線 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "78890994598313984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.i-cable.com/category/%e6%96%b0%e8%81%9e%e8%b3%87%e8%a8%8a/%e4%b8%ad%e5%9c%8b%e5%9c%a8%e7%b7%9a",
      "title": "有線新聞 - 中國在線",
      "type": "feed",
      "url": "rsshub://i-cable/news/%E4%B8%AD%E5%9C%8B%E5%9C%A8%E7%B7%9A"
    }
  ],
  "url": "www.i-cable.com/"
}
```
