# 米哈游 - 绝区零

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/mihoyo/zzz/:location?/:category?`
- Route Name: `绝区零`
- Example: `/mihoyo/zzz`
- URL: `zzz.mihoyo.com/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `Yeye-0426`
- Source Location: `zzz/news.ts`
- Source Module: `_None_`

## Description
#### 新闻 {#mi-ha-you-jue-qu-ling-xin-wen}

| 最新     | 新闻 | 公告   | 活动     |
| -------- | ---- | ------ | -------- |
| news-all | news | notice | activity |

## Parameters
- `location`: 区域，可选 `zh-cn`（国服，简中）或 `zh-tw`（国际服，繁中）
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
  - `zzz.mihoyo.com/news`
- `target`: `/zzz`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "#### 新闻 {#mi-ha-you-jue-qu-ling-xin-wen}\n\n| 最新     | 新闻 | 公告   | 活动     |\n| -------- | ---- | ------ | -------- |\n| news-all | news | notice | activity |",
  "example": "/mihoyo/zzz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "zzz/news.ts",
  "maintainers": [
    "Yeye-0426"
  ],
  "name": "绝区零",
  "parameters": {
    "category": "分类，见下表，默认为最新",
    "location": "区域，可选 `zh-cn`（国服，简中）或 `zh-tw`（国际服，繁中）"
  },
  "path": "/zzz/:location?/:category?",
  "radar": [
    {
      "source": [
        "zzz.mihoyo.com/news"
      ],
      "target": "/zzz"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "最新-绝区零 - Powered by RSSHub",
      "errorAt": "2026-08-06T21:25:12.083Z",
      "errorMessage": "[GET] \"https://api-takumi-static.mihoyo.com/content_v2_user/app/706fd13a87294881/getContentList?iPageSize=50&iPage=1&sLangKey=zh-cn&isPreview=0&iChanId=273\": <no response> fetch failed (Connect Timeout Error (attempted addresses: 124.14.14.51:443, 124.14.14.50:443, 124.14.14.55:443, 124.14.14.53:443, 124.14.14.52:443, 124.14.14.54:443, 124.14.14.56:443, 124.14.14.57:443, timeout: 10000ms))\n",
      "id": "182164256051058688",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zzz.mihoyo.com/news?category=273",
      "title": "最新-绝区零",
      "type": "feed",
      "url": "rsshub://mihoyo/zzz"
    },
    {
      "description": "最新-绝区零 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "205175880713752576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://zzz.mihoyo.com/news?category=273",
      "title": "最新-绝区零",
      "type": "feed",
      "url": "rsshub://mihoyo/zzz/zh-cn"
    }
  ],
  "url": "zzz.mihoyo.com/news"
}
```
