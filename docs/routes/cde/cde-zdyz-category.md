# 国家药品审评网站 - 指导原则专栏

## Coverage
`index-only`

## Route
- Namespace: `cde`
- Namespace Name: `国家药品审评网站`
- Route Path: `/cde/zdyz/:category`
- Route Name: `指导原则专栏`
- Example: `/cde/zdyz/domesticGuide`
- URL: `www.cde.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `TonyRL`
- Source Location: `zdyz.ts`
- Source Module: `_None_`

## Description
|    发布通告   |   征求意见  |
| :-----------: | :---------: |
| domesticGuide | opinionList |

## Parameters
- `category`: 类别，见下表


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
    "government"
  ],
  "description": "|    发布通告   |   征求意见  |\n| :-----------: | :---------: |\n| domesticGuide | opinionList |",
  "example": "/cde/zdyz/domesticGuide",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "zdyz.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "指导原则专栏",
  "parameters": {
    "category": "类别，见下表"
  },
  "path": "/zdyz/:category",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-09-13T01:51:47.585Z",
      "errorMessage": "Cannot read properties of undefined (reading 'set-cookie')\n",
      "id": "189505746675782662",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://cde/zdyz/domesticGuide"
    }
  ]
}
```
