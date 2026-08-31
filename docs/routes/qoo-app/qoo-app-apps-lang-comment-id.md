# QooApp - Game Store - Review

## Coverage
`index-only`

## Route
- Namespace: `qoo-app`
- Namespace Name: `QooApp`
- Route Path: `/qoo-app/apps/:lang?/comment/:id`
- Route Name: `Game Store - Review`
- Example: `/qoo-app/apps/en/comment/7675`
- URL: `apps.qoo-app.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `apps/comment.ts`
- Source Module: `_None_`

## Description
| 中文 | English | 한국어 | Español | 日本語 | ไทย | Tiếng Việt |
| ---- | ------- | ------ | ------- | ------ | --- | ---------- |
|      | en      | ko     | es      | ja     | th  | vi         |

## Parameters
- `lang`: Language, see the table below, empty means `中文`
- `id`: Game ID, can be found in URL


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
    "anime"
  ],
  "description": "| 中文 | English | 한국어 | Español | 日本語 | ไทย | Tiếng Việt |\n| ---- | ------- | ------ | ------- | ------ | --- | ---------- |\n|      | en      | ko     | es      | ja     | th  | vi         |",
  "example": "/qoo-app/apps/en/comment/7675",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "apps/comment.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Game Store - Review",
  "parameters": {
    "id": "Game ID, can be found in URL",
    "lang": "Language, see the table below, empty means `中文`"
  },
  "path": "/apps/:lang?/comment/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
