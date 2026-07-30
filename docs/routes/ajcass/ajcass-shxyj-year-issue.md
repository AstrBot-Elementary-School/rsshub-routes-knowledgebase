# 社科期刊网 - 社会学研究

## Coverage
`index-only`

## Route
- Namespace: `ajcass`
- Namespace Name: `社科期刊网`
- Route Path: `/ajcass/shxyj/:year?/:issue?`
- Route Name: `社会学研究`
- Example: `/ajcass/shxyj/2024/1`
- URL: `ajcass.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `CNYoki`
- Source Location: `shxyj.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `year`: Year of the issue, `null` for the lastest
- `issue`: Issue number, `null` for the lastest


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/ajcass/shxyj/2024/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 128,
  "location": "shxyj.ts",
  "maintainers": [
    "CNYoki"
  ],
  "name": "社会学研究",
  "parameters": {
    "issue": "Issue number, `null` for the lastest",
    "year": "Year of the issue, `null` for the lastest"
  },
  "path": "/shxyj/:year?/:issue?",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "社会学研究 2026年第3期 - Powered by RSSHub",
      "errorAt": "2026-07-08T05:53:03.219Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nAuthentication failed. Access denied.\n/ajcass/shxyj\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "83506691980410880",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://shxyj.ajcass.com/Magazine/?Year=2026&Issue=3",
      "title": "社会学研究 2026年第3期",
      "type": "feed",
      "url": "rsshub://ajcass/shxyj"
    },
    {
      "description": "社会学研究 2024年第1期 - Powered by RSSHub",
      "errorAt": "2026-07-19T22:35:38.449Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "82998945824254976",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://shxyj.ajcass.com/Magazine/?Year=2024&Issue=1",
      "title": "社会学研究 2024年第1期",
      "type": "feed",
      "url": "rsshub://ajcass/shxyj/2024/1"
    }
  ]
}
```
