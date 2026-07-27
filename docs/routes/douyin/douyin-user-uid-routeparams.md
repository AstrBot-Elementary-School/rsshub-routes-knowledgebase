# 抖音直播 - 博主

## Coverage
`index-only`

## Route
- Namespace: `douyin`
- Namespace Name: `抖音直播`
- Route Path: `/douyin/user/:uid/:routeParams?`
- Route Name: `博主`
- Example: `/douyin/user/MS4wLjABAAAARcAHmmF9mAG3JEixq_CdP72APhBlGlLVbN-1eBcPqao`
- URL: `douyin.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Max-Tortoise, Rongronggg9`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: uid，可在用户页面 URL 中找到
- `routeParams`: 额外参数，query string 格式，请参阅上面的表格


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
  - `douyin.com/user/:uid`
- `target`: `/user/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douyin/user/MS4wLjABAAAARcAHmmF9mAG3JEixq_CdP72APhBlGlLVbN-1eBcPqao",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 212,
  "location": "user.ts",
  "maintainers": [
    "Max-Tortoise",
    "Rongronggg9"
  ],
  "name": "博主",
  "parameters": {
    "routeParams": "额外参数，query string 格式，请参阅上面的表格",
    "uid": "uid，可在用户页面 URL 中找到"
  },
  "path": "/user/:uid/:routeParams?",
  "radar": [
    {
      "source": [
        "douyin.com/user/:uid"
      ],
      "target": "/user/:uid"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "姜胡说 - Powered by RSSHub",
      "errorAt": "2025-11-11T16:10:38.172Z",
      "errorMessage": "Could not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nEmpty post data. The request may be filtered by WAF.\n",
      "id": "188221989912814592",
      "image": "https://p3-pc.douyinpic.com/origin/aweme-avatar/mosaic-legacy_3149e000524a7b8745c42.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://www.douyin.com/user/MS4wLjABAAAAxaSHyjKQyfWHKjIS1mYbpxxEQZpT8ogl_eyks2M_Twc",
      "title": "姜胡说",
      "type": "feed",
      "url": "rsshub://douyin/user/MS4wLjABAAAAxaSHyjKQyfWHKjIS1mYbpxxEQZpT8ogl_eyks2M_Twc"
    },
    {
      "description": "伟布丁生活日记 - Powered by RSSHub",
      "errorAt": "2025-02-24T16:02:08.988Z",
      "errorMessage": "Could not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nEmpty post data. The request may be filtered by WAF.\n",
      "id": "116825524532749312",
      "image": "https://p3-pc.douyinpic.com/origin/aweme-avatar/mosaic-legacy_2e9e1000165a072193d95.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://www.douyin.com/user/MS4wLjABAAAARcAHmmF9mAG3JEixq_CdP72APhBlGlLVbN-1eBcPqao",
      "title": "伟布丁生活日记",
      "type": "feed",
      "url": "rsshub://douyin/user/MS4wLjABAAAARcAHmmF9mAG3JEixq_CdP72APhBlGlLVbN-1eBcPqao"
    }
  ]
}
```
