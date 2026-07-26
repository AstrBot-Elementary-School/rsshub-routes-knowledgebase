# 哔哩哔哩 bilibili - 直播搜索

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/live/search/:key/:order`
- Route Name: `直播搜索`
- Example: `/bilibili/live/search/dota/online`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `live`
- Maintainers: `Qixingchen`
- Source Location: `live-search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `key`: 搜索关键字
- `order`: 排序方式, live_time 开播时间, online 人气


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/bilibili/live/search/dota/online",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "live-search.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "name": "直播搜索",
  "parameters": {
    "key": "搜索关键字",
    "order": "排序方式, live_time 开播时间, online 人气"
  },
  "path": "/live/search/:key/:order",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "哔哩哔哩直播-漫展-最新开播 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57655769992100864",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://search.bilibili.com/live?keyword=%E6%BC%AB%E5%B1%95&order=live_time&coverType=user_cover&page=1&search_type=live",
      "title": "哔哩哔哩直播-漫展-最新开播",
      "type": "feed",
      "url": "rsshub://bilibili/live/search/%E6%BC%AB%E5%B1%95/live_time"
    },
    {
      "description": "哔哩哔哩直播-独夫之心-人气直播 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "198041982872060928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://search.bilibili.com/live?keyword=%E7%8B%AC%E5%A4%AB%E4%B9%8B%E5%BF%83&order=online&coverType=user_cover&page=1&search_type=live",
      "title": "哔哩哔哩直播-独夫之心-人气直播",
      "type": "feed",
      "url": "rsshub://bilibili/live/search/%E7%8B%AC%E5%A4%AB%E4%B9%8B%E5%BF%83/online"
    }
  ]
}
```
