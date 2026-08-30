# 无线新闻 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `tvb`
- Namespace Name: `无线新闻`
- Route Path: `/tvb/news/:category?/:language?`
- Route Name: `新闻`
- Example: `/tvb/news`
- URL: `tvb.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
分类

| 要聞  | 快訊    | 港澳  | 兩岸         | 國際  | 財經    | 體育   | 法庭       | 天氣    |
| ----- | ------- | ----- | ------------ | ----- | ------- | ------ | ---------- | ------- |
| focus | instant | local | greaterchina | world | finance | sports | parliament | weather |

语言

| 繁 | 简 |
| -- | -- |
| tc | sc |

## Parameters
- `category`: 分类，见下表，默认为要聞
- `language`: 语言，见下表


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
  - `tvb.com/:language/:category`
  - `tvb.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "分类\n\n| 要聞  | 快訊    | 港澳  | 兩岸         | 國際  | 財經    | 體育   | 法庭       | 天氣    |\n| ----- | ------- | ----- | ------------ | ----- | ------- | ------ | ---------- | ------- |\n| focus | instant | local | greaterchina | world | finance | sports | parliament | weather |\n\n语言\n\n| 繁 | 简 |\n| -- | -- |\n| tc | sc |",
  "example": "/tvb/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 153,
  "location": "news.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新闻",
  "parameters": {
    "category": "分类，见下表，默认为要聞",
    "language": "语言，见下表"
  },
  "path": "/news/:category?/:language?",
  "radar": [
    {
      "source": [
        "tvb.com/:language/:category",
        "tvb.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "TVB News - 要聞 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61348313469205504",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://inews-api.tvb.com/tc/focus",
      "title": "TVB News - 要聞",
      "type": "feed",
      "url": "rsshub://tvb/news"
    },
    {
      "description": "TVB News - 要闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68507536443122688",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://inews-api.tvb.com/sc/focus",
      "title": "TVB News - 要闻",
      "type": "feed",
      "url": "rsshub://tvb/news/focus/sc"
    }
  ]
}
```
