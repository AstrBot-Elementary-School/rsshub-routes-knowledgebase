# DW Deutsche Welle - News

## Coverage
`index-only`

## Route
- Namespace: `dw`
- Namespace Name: `DW Deutsche Welle`
- Route Path: `/dw/news/:lang?/:id?`
- Route Name: `News`
- Example: `/dw/news`
- URL: `dw.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
::: tip
Parameters can be obtained from the official website, for instance:
For the site <https://www.dw.com/de/deutschland/s-12321> the language code would be `de` and the category ID would be `s-1432`.
:::

## Parameters
- `lang`: Language, see below, default to en
- `id`: Category ID, see below, default to the id of the Top Stories Page of the language chosen


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: false

## Radar
### Rule 1
- `source`:
  - `www.dw.com/:lang/:name/:id`
- `target`: `/news/:lang/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\nParameters can be obtained from the official website, for instance:\nFor the site <https://www.dw.com/de/deutschland/s-12321> the language code would be `de` and the category ID would be `s-1432`.\n:::",
  "example": "/dw/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 207,
  "location": "news.ts",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "name": "News",
  "parameters": {
    "id": "Category ID, see below, default to the id of the Top Stories Page of the language chosen",
    "lang": "Language, see below, default to en"
  },
  "path": "/news/:lang?/:id?",
  "radar": [
    {
      "source": [
        "www.dw.com/:lang/:name/:id"
      ],
      "target": "/news/:lang/:id"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "德国之声中文频道通过文字、音频、视频相结合的多媒体方式提供以德国和欧洲为主同时包括世界政经资讯。我们的报道重点也包括中国政治、经济、社会的发展以及我们的中国受众群最关心感兴趣的各类话题。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82823881871653888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dw.com/zh/%E5%9C%A8%E7%BA%BF%E6%8A%A5%E5%AF%BC/s-9058",
      "title": "DW | 在线报导",
      "type": "feed",
      "url": "rsshub://dw/news/zh/s-9058"
    },
    {
      "description": "News, off-beat stories and analysis of German and international affairs. Dive deeper with our features from Europe and beyond. Watch our 24/7 TV stream. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "80448685677001728",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dw.com/en/top-stories/s-9097",
      "title": "DW | News and current affairs from Germany and around the world",
      "type": "feed",
      "url": "rsshub://dw/news"
    }
  ]
}
```
