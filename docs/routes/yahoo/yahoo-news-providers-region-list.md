# Yahoo - 新聞來源列表

## Coverage
`index-only`

## Route
- Namespace: `yahoo`
- Namespace Name: `Yahoo`
- Route Path: `/yahoo/news/providers/:region/list`
- Route Name: `新聞來源列表`
- Example: `/yahoo/news/providers/tw/list`
- URL: `news.yahoo.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL, williamgateszhao`
- Source Location: `news/provider-helper.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `region`: 地区, 同路由"新闻来源"中的支持地区, 即 hk 或 tw


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
  - `hk.news.yahoo.com/`
### Rule 2
- `source`:
  - `tw.news.yahoo.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/yahoo/news/providers/tw/list",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "news/provider-helper.ts",
  "maintainers": [
    "TonyRL",
    "williamgateszhao"
  ],
  "name": "新聞來源列表",
  "parameters": {
    "region": "地区, 同路由\"新闻来源\"中的支持地区, 即 hk 或 tw"
  },
  "path": "/news/providers/:region/list",
  "radar": [
    {
      "source": [
        "hk.news.yahoo.com/"
      ]
    },
    {
      "source": [
        "tw.news.yahoo.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "Yahoo 新聞 - 新聞來源列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84147667125450752",
      "image": "https://s.yimg.com/cv/apiv2/social/images/yahoo_default_logo-1200x1200.png",
      "ownerUserId": null,
      "siteUrl": "https://hk.news.yahoo.com/",
      "title": "Yahoo 新聞 - 新聞來源列表",
      "type": "feed",
      "url": "rsshub://yahoo/news/providers/hk/list"
    },
    {
      "description": "Yahoo 新聞 - 新聞來源列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84147601480398848",
      "image": "https://s.yimg.com/cv/apiv2/social/images/yahoo_default_logo-1200x1200.png",
      "ownerUserId": null,
      "siteUrl": "https://tw.news.yahoo.com/",
      "title": "Yahoo 新聞 - 新聞來源列表",
      "type": "feed",
      "url": "rsshub://yahoo/news/providers/tw/list"
    }
  ]
}
```
