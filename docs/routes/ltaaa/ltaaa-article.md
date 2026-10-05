# 龙腾网 - 网站翻译

## Coverage
`index-only`

## Route
- Namespace: `ltaaa`
- Namespace Name: `龙腾网`
- Route Path: `/ltaaa/article`
- Route Name: `网站翻译`
- Example: `/ltaaa/article`
- URL: `www.ltaaa.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `sgqy, nczitzk`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

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
  - `www.ltaaa.cn/article`
- `target`: `/article`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/ltaaa/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 12,
  "location": "article.ts",
  "maintainers": [
    "sgqy",
    "nczitzk"
  ],
  "name": "网站翻译",
  "path": "/article",
  "radar": [
    {
      "source": [
        "www.ltaaa.cn/article"
      ],
      "target": "/article"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:101:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "网贴翻译包括趣闻轶事,英语翻译,日语翻译,韩语翻译,德语翻译,西语翻译,法语翻译,翻译网 - Powered by RSSHub",
      "errorAt": "2026-07-19T17:39:58.669Z",
      "errorMessage": "[GET] \"https://www.ltaaa.cn/article\": 522 <none>\n",
      "id": "124430765697571840",
      "image": "https://www.ltaaa.cn/static/home/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.ltaaa.cn/article",
      "title": "网贴翻译 - 龙腾网",
      "type": "feed",
      "url": "rsshub://ltaaa/article"
    }
  ],
  "url": "www.ltaaa.cn",
  "view": 0
}
```
