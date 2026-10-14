# 哔哩哔哩 bilibili - UP 主频道的视频列表

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/channel/:uid/:sid/:embed?`
- Route Name: `UP 主频道的视频列表`
- Example: `/bilibili/user/channel/2267573/396050`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `weirongxu`
- Source Location: `user-channel.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `sid`: 频道 id, 可在频道的 URL 中找到
- `embed`: 默认为开启内嵌视频, 任意值为关闭


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
  - `space.bilibili.com/:uid/lists/:sid`
- `target`: `/user/channel/:uid/:sid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/channel/2267573/396050",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 55,
  "location": "user-channel.ts",
  "maintainers": [
    "weirongxu"
  ],
  "name": "UP 主频道的视频列表",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "sid": "频道 id, 可在频道的 URL 中找到",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/channel/:uid/:sid/:embed?",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid/lists/:sid"
      ],
      "target": "/user/channel/:uid/:sid"
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "DIYgod 的 bilibili 频道 - Powered by RSSHub",
      "errorAt": "2026-09-07T14:01:29.179Z",
      "errorMessage": "[GET] \"https://api.bilibili.com/x/series/series?series_id=396050\": 412 Precondition Failed\n",
      "id": "57641453192576000",
      "image": "https://i2.hdslb.com/bfs/face/9882696336717748a66cb70b0ed3f488f0cc9dad.jpg",
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/2267573/channel/seriesdetail?sid=396050",
      "title": "DIYgod 的 bilibili 频道 怪物猎人实况",
      "type": "feed",
      "url": "rsshub://bilibili/user/channel/2267573/396050"
    },
    {
      "description": "跟李沐学AI 的 bilibili 频道 - Powered by RSSHub",
      "errorAt": "2026-09-07T11:17:35.596Z",
      "errorMessage": "[GET] \"https://api.bilibili.com/x/series/series?series_id=358497\": 412 Precondition Failed\n",
      "id": "75758482619226112",
      "image": "https://i0.hdslb.com/bfs/face/15afabcda93279a5ab2f736513ad112e836a9701.jpg",
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/1567748478/channel/seriesdetail?sid=358497",
      "title": "跟李沐学AI 的 bilibili 频道 【完结】动手学深度学习 PyTorch版",
      "type": "feed",
      "url": "rsshub://bilibili/user/channel/1567748478/358497"
    }
  ]
}
```
