# 米哈游 - 原神

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/mihoyo/ys/:location?/:category?`
- Route Name: `原神`
- Example: `/mihoyo/ys`
- URL: `genshin.hoyoverse.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `ys/news.ts`
- Source Module: `_None_`

## Description
#### 新闻 {#mi-ha-you-yuan-shen-xin-wen}

| 最新   | 新闻 | 公告   | 活动     |
| ------ | ---- | ------ | -------- |
| latest | news | notice | activity |

## Parameters
- `location`: 区域，可选 `main`（简中）或 `zh-tw`（繁中）
- `category`: 分类，见下表，默认为最新


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
  - `genshin.hoyoverse.com/:location/news`
- `target`: `/ys/:location`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "#### 新闻 {#mi-ha-you-yuan-shen-xin-wen}\n\n| 最新   | 新闻 | 公告   | 活动     |\n| ------ | ---- | ------ | -------- |\n| latest | news | notice | activity |",
  "example": "/mihoyo/ys",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 57,
  "location": "ys/news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "原神",
  "parameters": {
    "category": "分类，见下表，默认为最新",
    "location": "区域，可选 `main`（简中）或 `zh-tw`（繁中）"
  },
  "path": "/ys/:location?/:category?",
  "radar": [
    {
      "source": [
        "genshin.hoyoverse.com/:location/news"
      ],
      "target": "/ys/:location"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "原神 - 最新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68834268354564096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ys.mihoyo.com/main/news/719",
      "title": "原神 - 最新",
      "type": "feed",
      "url": "rsshub://mihoyo/ys"
    },
    {
      "description": "原神 - 最新 - Powered by RSSHub",
      "errorAt": "2026-07-28T23:53:53.288Z",
      "errorMessage": "[GET] \"https://api-takumi-static.mihoyo.com/content_v2_user/app/16471662a82d418a/getContentList?iPage=1&sLangKey=zh-cn&iChanId=719&iPageSize=50\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 117.126.128.9:443, 117.126.128.10:443, 117.126.128.11:443, 117.126.128.12:443, 117.126.128.13:443, 117.126.128.14:443, 117.126.128.15:443, 117.126.128.16:443, timeout: 10000ms))\n",
      "id": "156266162055355392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ys.mihoyo.com/main/news/719",
      "title": "原神 - 最新",
      "type": "feed",
      "url": "rsshub://mihoyo/ys/main"
    }
  ]
}
```
