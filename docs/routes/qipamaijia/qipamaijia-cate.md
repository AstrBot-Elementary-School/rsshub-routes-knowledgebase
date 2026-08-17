# 奇葩买家秀 - 频道

## Coverage
`index-only`

## Route
- Namespace: `qipamaijia`
- Namespace Name: `奇葩买家秀`
- Route Path: `/qipamaijia/:cate?`
- Route Name: `频道`
- Example: `/qipamaijia/fuli`
- URL: `qipamaijia.com/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `Fatpandac, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `cate`: 频道名，可在对应网址中找到，默认为最新


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `qipamaijia.com/`
  - `qipamaijia.com/:cate`
- `target`: `/:cate`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/qipamaijia/fuli",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "Fatpandac",
    "nczitzk"
  ],
  "name": "频道",
  "parameters": {
    "cate": "频道名，可在对应网址中找到，默认为最新"
  },
  "path": "/:cate?",
  "radar": [
    {
      "source": [
        "qipamaijia.com/",
        "qipamaijia.com/:cate"
      ],
      "target": "/:cate"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "qipamaijia.com/"
}
```
