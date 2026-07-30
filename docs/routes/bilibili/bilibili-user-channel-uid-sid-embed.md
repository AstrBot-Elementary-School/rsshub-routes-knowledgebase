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
_None_

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
  "heat": 53,
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
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "跟李沐学AI 的 bilibili 频道 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75758482619226112",
      "image": "https://i0.hdslb.com/bfs/face/15afabcda93279a5ab2f736513ad112e836a9701.jpg",
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/1567748478/channel/seriesdetail?sid=358497",
      "title": "跟李沐学AI 的 bilibili 频道 【完结】动手学深度学习 PyTorch版",
      "type": "feed",
      "url": "rsshub://bilibili/user/channel/1567748478/358497"
    },
    {
      "description": "黑马程序员 的 bilibili 频道 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66328356640256000",
      "image": "https://i0.hdslb.com/bfs/face/a71b4dd6647ddf0c813bcf74e062edab9224cb0e.jpg",
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/37974444/channel/seriesdetail?sid=240490",
      "title": "黑马程序员 的 bilibili 频道 c/c++免费视频教程",
      "type": "feed",
      "url": "rsshub://bilibili/user/channel/37974444/240490"
    }
  ]
}
```
