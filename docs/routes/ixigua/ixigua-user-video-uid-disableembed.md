# 西瓜视频 - 用户视频投稿

## Coverage
`index-only`

## Route
- Namespace: `ixigua`
- Namespace Name: `西瓜视频`
- Route Path: `/ixigua/user/video/:uid/:disableEmbed?`
- Route Name: `用户视频投稿`
- Example: `/ixigua/user/video/4234740937`
- URL: `ixigua.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `FlashWingShadow, Fatpandac, pseudoyu`
- Source Location: `user-video.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在用户主页中找到
- `disableEmbed`: 默认为开启内嵌视频, 任意值为关闭


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
  - `ixigua.com/home/:uid`
- `target`: `/user/video/:uid`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/ixigua/user/video/4234740937",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 72,
  "location": "user-video.tsx",
  "maintainers": [
    "FlashWingShadow",
    "Fatpandac",
    "pseudoyu"
  ],
  "name": "用户视频投稿",
  "parameters": {
    "disableEmbed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在用户主页中找到"
  },
  "path": "/user/video/:uid/:disableEmbed?",
  "radar": [
    {
      "source": [
        "ixigua.com/home/:uid"
      ],
      "target": "/user/video/:uid"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "一个爱科普的豆比中学老师 - Powered by RSSHub",
      "errorAt": "2025-06-05T12:19:25.914Z",
      "errorMessage": "Failed to find SSR_HYDRATED_DATA\nFailed to find SSR_HYDRATED_DATA\n",
      "id": "77019657545759744",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ixigua.com/home/4234740937/?wid_try=1",
      "title": "李永乐老师 的西瓜视频",
      "type": "feed",
      "url": "rsshub://ixigua/user/video/4234740937"
    },
    {
      "description": "以心智观察新质 - Powered by RSSHub",
      "errorAt": "2025-06-05T10:27:31.877Z",
      "errorMessage": "Failed to find SSR_HYDRATED_DATA\nFailed to find SSR_HYDRATED_DATA\n",
      "id": "55214863323976729",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ixigua.com/home/62435616925/?wid_try=1",
      "title": "心智观察所 的西瓜视频",
      "type": "feed",
      "url": "rsshub://ixigua/user/video/62435616925"
    }
  ]
}
```
