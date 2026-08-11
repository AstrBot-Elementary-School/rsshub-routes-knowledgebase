# AIbase - AI日报

## Coverage
`index-only`

## Route
- Namespace: `aibase`
- Namespace Name: `AIbase`
- Route Path: `/aibase/daily`
- Route Name: `AI日报`
- Example: `/aibase/daily`
- URL: `www.aibase.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `3tuuu`
- Source Location: `daily.ts`
- Source Module: `_None_`

## Description
获取 AI 日报

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
  - `www.aibase.com/zh/daily`
- `target`: `/daily`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "获取 AI 日报",
  "example": "/aibase/daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 519,
  "location": "daily.ts",
  "maintainers": [
    "3tuuu"
  ],
  "name": "AI日报",
  "path": "/daily",
  "radar": [
    {
      "source": [
        "www.aibase.com/zh/daily"
      ],
      "target": "/daily"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "每天三分钟关注AI行业趋势 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "155494251060695040",
      "image": "https://top.aibase.com/_static/img/Frame@2x.eddfa3e.png",
      "ownerUserId": null,
      "siteUrl": "https://www.aibase.com/zh/daily",
      "title": "AI日报",
      "type": "feed",
      "url": "rsshub://aibase/daily"
    }
  ],
  "url": "www.aibase.com"
}
```
