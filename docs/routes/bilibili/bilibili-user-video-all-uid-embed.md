# 哔哩哔哩 bilibili - 用户所有视频

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/user/video-all/:uid/:embed?`
- Route Name: `用户所有视频`
- Example: `/bilibili/user/video-all/2267573`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `CcccFz`
- Source Location: `video-all.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `embed`: 默认为开启内嵌视频, 任意值为关闭


## Features
- `requirePuppeteer`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/video-all/2267573",
  "features": {
    "requirePuppeteer": true
  },
  "heat": 1264,
  "location": "video-all.ts",
  "maintainers": [
    "CcccFz"
  ],
  "name": "用户所有视频",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/video-all/:uid/:embed?",
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "技术爬爬虾 的 bilibili 所有视频 - Powered by RSSHub",
      "errorAt": "2026-08-25T07:54:26.811Z",
      "errorMessage": "[GET] \"https://api.bilibili.com/x/web-interface/card?mid=316183842\": 412 Precondition Failed\n",
      "id": "82801159002601472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/316183842/video",
      "title": "技术爬爬虾",
      "type": "feed",
      "url": "rsshub://bilibili/user/video-all/316183842"
    },
    {
      "description": "小Lin说 的 bilibili 所有视频 - Powered by RSSHub",
      "errorAt": "2026-08-26T23:43:23.393Z",
      "errorMessage": "[GET] \"https://api.bilibili.com/x/web-interface/card?mid=520819684\": 412 Precondition Failed\nCould not find Chrome (ver. 123.0.6312.86). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\n",
      "id": "69028952282503168",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://space.bilibili.com/520819684/video",
      "title": "小Lin说",
      "type": "feed",
      "url": "rsshub://bilibili/user/video-all/520819684"
    }
  ]
}
```
