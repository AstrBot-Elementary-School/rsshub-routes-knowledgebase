# 斗鱼直播 - 直播间开播

## Coverage
`index-only`

## Route
- Namespace: `douyu`
- Namespace Name: `斗鱼直播`
- Route Path: `/douyu/room/:id`
- Route Name: `直播间开播`
- Example: `/douyu/room/24422`
- URL: `www.douyu.com`
- Language: `_None_`
- Categories: `live`
- Maintainers: `DIYgod, ChaosTong`
- Source Location: `room.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 直播间 id, 可在主播直播间页 URL 中找到


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
  - `www.douyu.com/:id`
  - `www.douyu.com/`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/douyu/room/24422",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 93,
  "location": "room.ts",
  "maintainers": [
    "DIYgod",
    "ChaosTong"
  ],
  "name": "直播间开播",
  "parameters": {
    "id": "直播间 id, 可在主播直播间页 URL 中找到"
  },
  "path": "/room/:id",
  "radar": [
    {
      "source": [
        "www.douyu.com/:id",
        "www.douyu.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "寅子的斗鱼直播间 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73704015177969664",
      "image": "https://rpic.douyucdn.cn/asrpic/260805/71415_src_2305.avif/dy4",
      "ownerUserId": null,
      "siteUrl": "https://www.douyu.com/71415",
      "title": "寅子的斗鱼直播间",
      "type": "feed",
      "url": "rsshub://douyu/room/71415"
    },
    {
      "description": "yyfyyf的斗鱼直播间 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62335921117247488",
      "image": "https://rpic.douyucdn.cn/asrpic/260802/9999_src_2319.avif/dy4",
      "ownerUserId": null,
      "siteUrl": "https://www.douyu.com/9999",
      "title": "yyfyyf的斗鱼直播间",
      "type": "feed",
      "url": "rsshub://douyu/room/9999"
    }
  ]
}
```
