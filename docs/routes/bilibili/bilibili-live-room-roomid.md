# 哔哩哔哩 bilibili - 直播开播

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/live/room/:roomID`
- Route Name: `直播开播`
- Example: `/bilibili/live/room/3`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `live`
- Maintainers: `Qixingchen`
- Source Location: `live-room.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `roomID`: 房间号, 可在直播间 URL 中找到, 长短号均可


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
  - `live.bilibili.com/:roomID`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/bilibili/live/room/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 228,
  "location": "live-room.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "name": "直播开播",
  "parameters": {
    "roomID": "房间号, 可在直播间 URL 中找到, 长短号均可"
  },
  "path": "/live/room/:roomID",
  "radar": [
    {
      "source": [
        "live.bilibili.com/:roomID"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "泛式 直播间开播状态 - Powered by RSSHub",
      "errorAt": "2026-08-16T05:14:08.885Z",
      "errorMessage": "500 \n",
      "id": "55242372435247104",
      "image": "https://i0.hdslb.com/bfs/face/2608aaa45309c77ac88fbfaa40e160b8c7892985.jpg",
      "ownerUserId": null,
      "siteUrl": "https://live.bilibili.com/33989",
      "title": "泛式 直播间开播状态",
      "type": "feed",
      "url": "rsshub://bilibili/live/room/33989"
    },
    {
      "description": "EdmundDZhang 直播间开播状态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55139597974077440",
      "image": "https://i1.hdslb.com/bfs/face/50900541a74f7875867c38a1e8e572b44b388060.jpg",
      "ownerUserId": null,
      "siteUrl": "https://live.bilibili.com/5050",
      "title": "EdmundDZhang 直播间开播状态",
      "type": "feed",
      "url": "rsshub://bilibili/live/room/5050"
    }
  ]
}
```
