# 哔哩哔哩 bilibili - 直播分区

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/live/area/:areaID/:order`
- Route Name: `直播分区`
- Example: `/bilibili/live/area/207/online`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `live`
- Maintainers: `Qixingchen`
- Source Location: `live-area.ts`
- Source Module: `_None_`

## Description
::: warning
由于接口未提供开播时间，如果直播间未更换标题与分区，将视为一次。如果直播间更换分区与标题，将视为另一项
:::

## Parameters
- `areaID`: 分区 ID 分区增删较多, 可通过 [分区列表](https://api.live.bilibili.com/room/v1/Area/getList) 查询
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
  "description": "::: warning\n由于接口未提供开播时间，如果直播间未更换标题与分区，将视为一次。如果直播间更换分区与标题，将视为另一项\n:::",
  "example": "/bilibili/live/area/207/online",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 32,
  "location": "live-area.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "name": "直播分区",
  "parameters": {
    "areaID": "分区 ID 分区增删较多, 可通过 [分区列表](https://api.live.bilibili.com/room/v1/Area/getList) 查询",
    "order": "排序方式, live_time 开播时间, online 人气"
  },
  "path": "/live/area/:areaID/:order",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "哔哩哔哩直播-娱乐·舞见分区-人气直播 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56218629867262976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://live.bilibili.com/p/eden/area-tags?parentAreaId=1&areaId=207",
      "title": "哔哩哔哩直播-娱乐·舞见分区-人气直播",
      "type": "feed",
      "url": "rsshub://bilibili/live/area/207/online"
    },
    {
      "description": "哔哩哔哩直播-生活·生活杂谈分区-人气直播 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "77359644443453440",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://live.bilibili.com/p/eden/area-tags?parentAreaId=10&areaId=646",
      "title": "哔哩哔哩直播-生活·生活杂谈分区-人气直播",
      "type": "feed",
      "url": "rsshub://bilibili/live/area/646/online"
    }
  ]
}
```
