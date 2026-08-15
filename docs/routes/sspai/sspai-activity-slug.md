# 少数派 sspai - 作者动态

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/sspai/activity/:slug`
- Route Name: `作者动态`
- Example: `/sspai/activity/urfp0d9i`
- URL: `sspai.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `umm233`
- Source Location: `activity.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `slug`: 作者 slug，可在作者主页URL中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `sspai.com/u/:id/updates`
- `target`: `/activity/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/activity/urfp0d9i",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 174,
  "location": "activity.ts",
  "maintainers": [
    "umm233"
  ],
  "name": "作者动态",
  "parameters": {
    "slug": "作者 slug，可在作者主页URL中找到"
  },
  "path": "/activity/:slug",
  "radar": [
    {
      "source": [
        "sspai.com/u/:id/updates"
      ],
      "target": "/activity/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(4) ] to not include 'https://sspai.com/post/65408'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "少数派用户「玉树芝兰」的动态更新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58311597468054534",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/u/a5xddvxl/updates",
      "title": "少数派用户「玉树芝兰」动态更新",
      "type": "feed",
      "url": "rsshub://sspai/activity/a5xddvxl"
    },
    {
      "description": "少数派用户「西郊次生林」的动态更新 - Powered by RSSHub",
      "errorAt": "2026-08-14T02:13:14.466Z",
      "errorMessage": "502 Bad Gateway\nUnknown action key: community_reply_topic_comment_reply\n",
      "id": "143174175969882112",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sspai.com/u/05c3mst0/updates",
      "title": "少数派用户「西郊次生林」动态更新",
      "type": "feed",
      "url": "rsshub://sspai/activity/05c3mst0"
    }
  ]
}
```
