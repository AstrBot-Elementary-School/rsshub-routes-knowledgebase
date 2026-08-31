# 网易公开课 - 用户听歌排行

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/music/user/playrecords/:uid/:type?`
- Route Name: `用户听歌排行`
- Example: `/163/music/user/playrecords/45441555/1`
- URL: `163.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `alfredcai`
- Source Location: `music/userplayrecords.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 uid, 可在用户主页 URL 中找到
- `type`: 排行榜类型，0所有时间(默认)，1最近一周


## Features
- `requireConfig`: [{"description": "网易云音乐登陆后的 cookie 值，可在浏览器控制台通过`document.cookie`获取。", "name": "NCM_COOKIES", "optional": true}]
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
    "multimedia"
  ],
  "example": "/163/music/user/playrecords/45441555/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "网易云音乐登陆后的 cookie 值，可在浏览器控制台通过`document.cookie`获取。",
        "name": "NCM_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "music/userplayrecords.tsx",
  "maintainers": [
    "alfredcai"
  ],
  "name": "用户听歌排行",
  "parameters": {
    "type": "排行榜类型，0所有时间(默认)，1最近一周",
    "uid": "用户 uid, 可在用户主页 URL 中找到"
  },
  "path": "/music/user/playrecords/:uid/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-09-04T16:17:42.394Z",
      "errorMessage": "Cannot read properties of undefined (reading 'date')\n",
      "id": "186422945668491338",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://163/music/user/playrecords/253142666"
    }
  ]
}
```
