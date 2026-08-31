# Apple - Newsroom (中国大陆)

## Coverage
`index-only`

## Route
- Namespace: `apple`
- Namespace Name: `Apple`
- Route Path: `/apple/newsroom`
- Route Name: `Newsroom (中国大陆)`
- Example: `/apple/newsroom`
- URL: `www.apple.com.cn/newsroom`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `LinxHex`
- Source Location: `newsroom.ts`
- Source Module: `_None_`

## Description
The official source for news about Apple, from Apple. Read press releases, get updates, watch video and download images.

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.apple.com.cn/newsroom`
  - `www.apple.com.cn/newsroom/:year/:month/:slug`
- `target`: `/newsroom`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "The official source for news about Apple, from Apple. Read press releases, get updates, watch video and download images.",
  "example": "/apple/newsroom",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 7,
  "location": "newsroom.ts",
  "maintainers": [
    "LinxHex"
  ],
  "name": "Newsroom (中国大陆)",
  "path": "/newsroom",
  "radar": [
    {
      "source": [
        "www.apple.com.cn/newsroom",
        "www.apple.com.cn/newsroom/:year/:month/:slug"
      ],
      "target": "/newsroom"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "Apple 新闻中心是 Apple 新闻的来源。阅读新闻稿、获取最新消息、观看视频和下载图片。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "264963271334883328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.apple.com.cn/newsroom/",
      "title": "Apple Newsroom (中国大陆)",
      "type": "feed",
      "url": "rsshub://apple/newsroom"
    }
  ],
  "url": "www.apple.com.cn/newsroom",
  "view": 0,
  "zh": {
    "description": "Apple 新闻中心是 Apple 新闻的来源。阅读新闻稿、获取最新消息、观看视频和下载图片。",
    "name": "新闻中心（中国大陆）"
  }
}
```
