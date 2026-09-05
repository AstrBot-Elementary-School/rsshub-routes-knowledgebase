# DataGuidance - News

## Coverage
`index-only`

## Route
- Namespace: `dataguidance`
- Namespace Name: `DataGuidance`
- Route Path: `/dataguidance/news`
- Route Name: `News`
- Example: `/dataguidance/news`
- URL: `https://www.dataguidance.com/info?article_type=news_post`
- Language: `_None_`
- Categories: `other`
- Maintainers: `harveyqiu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dataguidance.com/info`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/dataguidance/news",
  "heat": 21,
  "location": "index.ts",
  "maintainers": [
    "harveyqiu"
  ],
  "name": "News",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.dataguidance.com/info"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "Data Guidance News - Powered by RSSHub",
      "errorAt": "2026-09-04T10:02:46.968Z",
      "errorMessage": "Failed to fetch\n",
      "id": "67733611004811264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dataguidance.com/info?article_type=news_post",
      "title": "Data Guidance News",
      "type": "feed",
      "url": "rsshub://dataguidance/news"
    }
  ],
  "url": "https://www.dataguidance.com/info?article_type=news_post"
}
```
