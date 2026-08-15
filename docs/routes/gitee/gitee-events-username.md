# Gitee - 用户公开动态

## Coverage
`index-only`

## Route
- Namespace: `gitee`
- Namespace Name: `Gitee`
- Route Path: `/gitee/events/:username`
- Route Name: `用户公开动态`
- Example: `/gitee/events/y_project`
- URL: `gitee.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `users/events.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: 用户名


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
  - `gitee.com/:username`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gitee/events/y_project",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "users/events.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "用户公开动态",
  "parameters": {
    "username": "用户名"
  },
  "path": "/events/:username",
  "radar": [
    {
      "source": [
        "gitee.com/:username"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "zepc-hhy - 公开动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "1161384219914403840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gitee.com/zepc-hhy",
      "title": "zepc-hhy - 公开动态",
      "type": "feed",
      "url": "rsshub://gitee/events/zepc-hhy"
    },
    {
      "description": "callmer - 公开动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "158419992977388544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gitee.com/callmer",
      "title": "callmer - 公开动态",
      "type": "feed",
      "url": "rsshub://gitee/events/callmer"
    }
  ]
}
```
