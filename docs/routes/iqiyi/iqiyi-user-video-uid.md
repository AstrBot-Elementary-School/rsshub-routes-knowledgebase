# 爱奇艺 - 用户视频

## Coverage
`index-only`

## Route
- Namespace: `iqiyi`
- Namespace Name: `爱奇艺`
- Route Path: `/iqiyi/user/video/:uid`
- Route Name: `用户视频`
- Example: `/iqiyi/user/video/2289191062`
- URL: `iq.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `talengu, JimenezLi`
- Source Location: `video.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户名


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
  - `iqiyi.com/u/:uid/*`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/iqiyi/user/video/2289191062",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "video.ts",
  "maintainers": [
    "talengu",
    "JimenezLi"
  ],
  "name": "用户视频",
  "parameters": {
    "uid": "用户名"
  },
  "path": "/user/video/:uid",
  "radar": [
    {
      "source": [
        "iqiyi.com/u/:uid/*"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
