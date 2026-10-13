# 观察者网 - 头条

## Coverage
`index-only`

## Route
- Namespace: `guancha`
- Namespace Name: `观察者网`
- Route Path: `/guancha/headline`
- Route Name: `头条`
- Example: `/guancha/headline`
- URL: `guancha.cn/GuanChaZheTouTiao`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `headline.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `guancha.cn/GuanChaZheTouTiao`
  - `guancha.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/guancha/headline",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 720,
  "location": "headline.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "头条",
  "parameters": {},
  "path": "/headline",
  "radar": [
    {
      "source": [
        "guancha.cn/GuanChaZheTouTiao",
        "guancha.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:101:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "观察者网 - 头条 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54806769974844419",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.guancha.cn/GuanChaZheTouTiao/list_1.shtml",
      "title": "观察者网 - 头条",
      "type": "feed",
      "url": "rsshub://guancha/headline"
    }
  ],
  "url": "guancha.cn/GuanChaZheTouTiao"
}
```
