# 网易公开课 - 用户歌单

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/163/music/user/playlist/:uid`
- Route Name: `用户歌单`
- Example: `/163/music/user/playlist/45441555`
- URL: `163.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `DIYgod`
- Source Location: `music/userplaylist.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 uid, 可在用户主页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `music.163.com/user/home`
- `target`: `/music/user/playlist/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/163/music/user/playlist/45441555",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 2,
  "location": "music/userplaylist.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "name": "用户歌单",
  "parameters": {
    "uid": "用户 uid, 可在用户主页 URL 中找到"
  },
  "path": "/music/user/playlist/:uid",
  "radar": [
    {
      "source": [
        "music.163.com/user/home"
      ],
      "target": "/music/user/playlist/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-09-04T16:17:02.496Z",
      "errorMessage": "Cannot read properties of undefined (reading 'date')\n",
      "id": "186422945668491339",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://163/music/user/playlist/253142666"
    }
  ]
}
```
