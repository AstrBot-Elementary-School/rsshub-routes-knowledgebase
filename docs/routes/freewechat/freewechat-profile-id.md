# 自由微信 - 公众号

## Coverage
`index-only`

## Route
- Namespace: `freewechat`
- Namespace Name: `自由微信`
- Route Path: `/freewechat/profile/:id`
- Route Name: `公众号`
- Example: `/freewechat/profile/MzI5NTUxNzk3OA==`
- URL: `freewechat.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `profile.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 公众号 ID，可在URL中找到


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
  - `freewechat.com/profile/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/freewechat/profile/MzI5NTUxNzk3OA==",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 168,
  "location": "profile.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "公众号",
  "parameters": {
    "id": "公众号 ID，可在URL中找到"
  },
  "path": "/profile/:id",
  "radar": [
    {
      "source": [
        "freewechat.com/profile/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "刑法库 | 自由微信 | FreeWeChat - Powered by RSSHub",
      "errorAt": "2025-11-26T12:46:04.860Z",
      "errorMessage": "[GET] \"https://freewechat.com/a/MzI5NTUxNzk3OA==/2247492264/1\": 403 Forbidden\n[GET] \"https://freewechat.com/a/MzI5NTUxNzk3OA==/2247492264/1\": 403 Forbidden\n",
      "id": "60004603567114240",
      "image": "https://freewechat.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://freewechat.com/profile/MzI5NTUxNzk3OA==",
      "title": "刑法库 | 自由微信 | FreeWeChat",
      "type": "feed",
      "url": "rsshub://freewechat/profile/MzI5NTUxNzk3OA=="
    },
    {
      "description": "游戏葡萄 | 自由微信 | FreeWeChat - Powered by RSSHub",
      "errorAt": "2025-11-26T10:25:21.045Z",
      "errorMessage": "[GET] \"https://freewechat.com/a/MjM5OTc2ODUxMw==/2649992634/1\": 403 Forbidden\n",
      "id": "77190515673860096",
      "image": "https://freewechat.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://freewechat.com/profile/MjM5OTc2ODUxMw==",
      "title": "游戏葡萄 | 自由微信 | FreeWeChat",
      "type": "feed",
      "url": "rsshub://freewechat/profile/MjM5OTc2ODUxMw=="
    }
  ]
}
```
