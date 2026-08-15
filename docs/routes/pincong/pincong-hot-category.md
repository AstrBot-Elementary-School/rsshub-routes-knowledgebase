# 品葱 - 精选

## Coverage
`index-only`

## Route
- Namespace: `pincong`
- Namespace Name: `品葱`
- Route Path: `/pincong/hot/:category?`
- Route Name: `精选`
- Example: `/pincong/hot`
- URL: `pincong.rocks`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `zphw`
- Source Location: `hot.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分类，与官网分类 URL `category-` 后的数字对应，默认为全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/pincong/hot",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 101,
  "location": "hot.ts",
  "maintainers": [
    "zphw"
  ],
  "name": "精选",
  "parameters": {
    "category": "分类，与官网分类 URL `category-` 后的数字对应，默认为全部"
  },
  "path": "/hot/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "品葱 - 精选 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53908061985105940",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://pincong.rocks/hot/",
      "title": "品葱 - 精选",
      "type": "feed",
      "url": "rsshub://pincong/hot"
    }
  ]
}
```
