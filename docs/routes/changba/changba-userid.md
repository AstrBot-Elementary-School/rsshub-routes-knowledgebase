# 唱吧 - 用户

## Coverage
`index-only`

## Route
- Namespace: `changba`
- Namespace Name: `唱吧`
- Route Path: `/changba/:userid`
- Route Name: `用户`
- Example: `/changba/skp6hhF59n48R-UpqO3izw`
- URL: `changba.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `kt286, xizeyoupan, pseudoyu`
- Source Location: `user.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `userid`: 用户ID, 可在对应分享页面的 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `changba.com/s/:userid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/changba/skp6hhF59n48R-UpqO3izw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "heat": 10,
  "location": "user.tsx",
  "maintainers": [
    "kt286",
    "xizeyoupan",
    "pseudoyu"
  ],
  "name": "用户",
  "parameters": {
    "userid": "用户ID, 可在对应分享页面的 URL 中找到"
  },
  "path": "/:userid",
  "radar": [
    {
      "source": [
        "changba.com/s/:userid"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "你那么孤单却要说着一个人真好 - 唱吧 - Powered by RSSHub",
      "errorAt": "2026-07-08T13:02:09.054Z",
      "errorMessage": "Cannot create property 'description' on string 'null'\n",
      "id": "71352051843670016",
      "image": "https://aliimg.changba.com/cache/photo/53525835_200_200.jpg",
      "ownerUserId": null,
      "siteUrl": "https://changba.com/wap/index.php?s=YYA5JcoVb7nQKfvVSWnIBg",
      "title": "你那么孤单却要说着一个人真好 - 唱吧",
      "type": "feed",
      "url": "rsshub://changba/YYA5JcoVb7nQKfvVSWnIBg"
    },
    {
      "description": "- 唱吧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "122101353169483776",
      "image": "https://aliimg.changba.com/cache/photo/877051009_200_200.jpg",
      "ownerUserId": null,
      "siteUrl": "https://changba.com/wap/index.php?s=LkE053-d9BPdUsIBPMn2Bg",
      "title": "- 唱吧",
      "type": "feed",
      "url": "rsshub://changba/LkE053-d9BPdUsIBPMn2Bg"
    }
  ],
  "view": 4
}
```
