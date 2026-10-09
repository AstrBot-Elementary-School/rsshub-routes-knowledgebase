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
  "heat": 0,
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
  "topFeeds": []
}
```
