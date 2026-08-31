# 抖音直播 - 标签

## Coverage
`index-only`

## Route
- Namespace: `douyin`
- Namespace Name: `抖音直播`
- Route Path: `/douyin/hashtag/:cid/:routeParams?`
- Route Name: `标签`
- Example: `/douyin/hashtag/1592824105719812`
- URL: `douyin.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `hashtag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `cid`: 标签 ID，可在标签页面 URL 中找到
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
  - `douyin.com/hashtag/:cid`
- `target`: `/hashtag/:cid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douyin/hashtag/1592824105719812",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "hashtag.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "标签",
  "parameters": {
    "cid": "标签 ID，可在标签页面 URL 中找到",
    "routeParams": "额外参数，query string 格式，请参阅上面的表格"
  },
  "path": "/hashtag/:cid/:routeParams?",
  "radar": [
    {
      "source": [
        "douyin.com/hashtag/:cid"
      ],
      "target": "/hashtag/:cid"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
