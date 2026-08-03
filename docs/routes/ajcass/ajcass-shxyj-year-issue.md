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
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
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
