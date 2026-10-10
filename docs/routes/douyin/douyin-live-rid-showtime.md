# 抖音直播 - 直播间开播

## Coverage
`index-only`

## Route
- Namespace: `douyin`
- Namespace Name: `抖音直播`
- Route Path: `/douyin/live/:rid/:showTime?`
- Route Name: `直播间开播`
- Example: `/douyin/live/685317364746`
- URL: `douyin.com`
- Language: `_None_`
- Categories: `live`
- Maintainers: `TonyRL`
- Source Location: `live.ts`
- Source Module: `_None_`

## Description
优先读取公开页面中的直播状态，必要时使用 Playwright 读取页面或直播间接口。showTime 开启时，标题后显示 RSSHub 本场首次检测时间（UTC+8），并非源站实际开播时刻，也不会作为 pubDate。时间按本场真实 room ID 缓存 30 天，重复读取不会延长有效期。内存缓存重启或清除缓存会重置记录，建议使用 Redis 保持记录稳定。

## Parameters
- `rid`: 直播间 id, 可在主播直播间页 URL 中找到
- `showTime`: 是否在标题后添加本场首次检测时间，0/1/true/false，默认 false。


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `live.douyin.com/:rid`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "description": "优先读取公开页面中的直播状态，必要时使用 Playwright 读取页面或直播间接口。showTime 开启时，标题后显示 RSSHub 本场首次检测时间（UTC+8），并非源站实际开播时刻，也不会作为 pubDate。时间按本场真实 room ID 缓存 30 天，重复读取不会延长有效期。内存缓存重启或清除缓存会重置记录，建议使用 Redis 保持记录稳定。",
  "example": "/douyin/live/685317364746",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "live.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "直播间开播",
  "parameters": {
    "rid": "直播间 id, 可在主播直播间页 URL 中找到",
    "showTime": "是否在标题后添加本场首次检测时间，0/1/true/false，默认 false。"
  },
  "path": "/live/:rid/:showTime?",
  "radar": [
    {
      "source": [
        "live.douyin.com/:rid"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "欢迎来到碳碳啊的抖音直播间，碳碳啊与大家一起记录美好生活 - 抖音直播 - Powered by RSSHub",
      "errorAt": "2026-10-09T10:55:46.699Z",
      "errorMessage": "Invalid room ID. Room ID should be a number.\n",
      "id": "1244807888635822080",
      "image": "https://p11.douyinpic.com/origin/aweme-avatar/tos-cn-avt-0015_7638c3c366c0dd37b02949cb6415915c.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://live.douyin.com/mxw0617.",
      "title": "碳碳啊的抖音直播间 - 抖音直播",
      "type": "feed",
      "url": "rsshub://douyin/live/mxw0617."
    },
    {
      "description": "欢迎来到五月儿的抖音直播间，五月儿与大家一起记录美好生活 - 抖音直播 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "130245278681074688",
      "image": "https://p3.douyinpic.com/origin/aweme-avatar/tos-cn-avt-0015_e8d1c5dc1085920d4e0ef2f61c57a318.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://live.douyin.com/942387616310",
      "title": "五月儿的抖音直播间 - 抖音直播",
      "type": "feed",
      "url": "rsshub://douyin/live/942387616310"
    }
  ]
}
```
