# 抖音直播 - 直播间开播

## Coverage
`index-only`

## Route
- Namespace: `douyin`
- Namespace Name: `抖音直播`
- Route Path: `/douyin/live/:rid`
- Route Name: `直播间开播`
- Example: `/douyin/live/685317364746`
- URL: `douyin.com`
- Language: `_None_`
- Categories: `live`
- Maintainers: `TonyRL`
- Source Location: `live.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `rid`: 直播间 id, 可在主播直播间页 URL 中找到


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
  "example": "/douyin/live/685317364746",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 189,
  "location": "live.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "直播间开播",
  "parameters": {
    "rid": "直播间 id, 可在主播直播间页 URL 中找到"
  },
  "path": "/live/:rid",
  "radar": [
    {
      "source": [
        "live.douyin.com/:rid"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "欢迎来到陈伯(全能王)的抖音直播间，陈伯(全能王)与大家一起记录美好生活 - 抖音直播 - Powered by RSSHub",
      "errorAt": "2026-05-11T10:59:01.774Z",
      "errorMessage": "Could not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nCannot read properties of undefined (reading 'status_code')\n",
      "id": "72456550295913472",
      "image": "https://p3.douyinpic.com/origin/aweme-avatar/tos-cn-avt-0015_bed947cccd9ad785a0a96dbec1fb2fe3.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://live.douyin.com/921169302662",
      "title": "陈伯(全能王)的抖音直播间 - 抖音直播",
      "type": "feed",
      "url": "rsshub://douyin/live/921169302662"
    },
    {
      "description": "欢迎来到JJ斗地主的抖音直播间，JJ斗地主与大家一起记录美好生活 - 抖音直播 - Powered by RSSHub",
      "errorAt": "2026-07-19T11:55:53.182Z",
      "errorMessage": "Cannot read properties of undefined (reading 'status_code')\n",
      "id": "59212657080258560",
      "image": "https://p26.douyinpic.com/origin/aweme-avatar/tos-cn-avt-0015_970a4d312023de54cbac3d0f9e0e77f8.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://live.douyin.com/685317364746",
      "title": "JJ斗地主的抖音直播间 - 抖音直播",
      "type": "feed",
      "url": "rsshub://douyin/live/685317364746"
    }
  ]
}
```
