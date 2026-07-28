# Yahoo - 新聞來源

## Coverage
`index-only`

## Route
- Namespace: `yahoo`
- Namespace Name: `Yahoo`
- Route Path: `/yahoo/news/provider/:region/:providerId`
- Route Name: `新聞來源`
- Example: `/yahoo/news/provider/tw/yahoo_tech_tw_942`
- URL: `news.yahoo.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL, williamgateszhao`
- Source Location: `news/provider.ts`
- Source Module: `_None_`

## Description
`Region`

| 香港 | 台灣 |
| ---- | ---- |
| hk   | tw   |

`ProviderId`

除了可以通过路由 "新聞來源列表" 获得外，也可通过 hk.news.yahoo.com/archive 和 tw\.news.yahoo.com/archive 选择 "新闻来源" 后通过页面 Url 来获得。

例如 hk.news.yahoo.com/yahoo\_movies\_hk\_660-- 所有分類 /archive, `yahoo_movies_hk_660` 就是 ProviderId 。

## Parameters
- `region`: 地區, hk 或 tw, 分别表示香港雅虎和台湾雅虎
- `providerId`: 新聞來源 ID, 可透過路由"新聞來源列表"獲得


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
  "description": "`Region`\n\n| 香港 | 台灣 |\n| ---- | ---- |\n| hk   | tw   |\n\n`ProviderId`\n\n除了可以通过路由 \"新聞來源列表\" 获得外，也可通过 hk.news.yahoo.com/archive 和 tw\\.news.yahoo.com/archive 选择 \"新闻来源\" 后通过页面 Url 来获得。\n\n例如 hk.news.yahoo.com/yahoo\\_movies\\_hk\\_660-- 所有分類 /archive, `yahoo_movies_hk_660` 就是 ProviderId 。",
  "example": "/yahoo/news/provider/tw/yahoo_tech_tw_942",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 195,
  "location": "news/provider.ts",
  "maintainers": [
    "TonyRL",
    "williamgateszhao"
  ],
  "name": "新聞來源",
  "parameters": {
    "providerId": "新聞來源 ID, 可透過路由\"新聞來源列表\"獲得",
    "region": "地區, hk 或 tw, 分别表示香港雅虎和台湾雅虎"
  },
  "path": "/news/provider/:region/:providerId",
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
      "description": "Yahoo 新聞 - - Powered by RSSHub",
      "errorAt": "2026-07-08T14:02:09.976Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n[GET] \"https://hk.news.yahoo.com/archive\": <no response> fetch failed\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "66154144789164034",
      "image": "https://s.yimg.com/cv/apiv2/social/images/yahoo_default_logo-1200x1200.png",
      "ownerUserId": null,
      "siteUrl": "https://hk.news.yahoo.com/",
      "title": "Yahoo 新聞 -",
      "type": "feed",
      "url": "rsshub://yahoo/news/provider/hk/afp.com.hk"
    },
    {
      "description": "Yahoo 新聞 - Yahoo Tech - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69691546140683264",
      "image": "https://s.yimg.com/cv/apiv2/social/images/yahoo_default_logo-1200x1200.png",
      "ownerUserId": null,
      "siteUrl": "https://tw.news.yahoo.com/yahoo_tech_tw_942--%E6%89%80%E6%9C%89%E9%A1%9E%E5%88%A5/archive",
      "title": "Yahoo 新聞 - Yahoo Tech",
      "type": "feed",
      "url": "rsshub://yahoo/news/provider/tw/yahoo_tech_tw_942"
    }
  ]
}
```
