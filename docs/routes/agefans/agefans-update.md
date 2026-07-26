# AGE 动漫 - 最近更新

## Coverage
`index-only`

## Route
- Namespace: `agefans`
- Namespace Name: `AGE 动漫`
- Route Path: `/agefans/update`
- Route Name: `最近更新`
- Example: `/agefans/update`
- URL: `agemys.org/update`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `update.ts`
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
  - `agemys.org/update`
  - `agemys.org/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/agefans/update",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 212,
  "location": "update.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "最近更新",
  "parameters": {},
  "path": "/update",
  "radar": [
    {
      "source": [
        "agemys.org/update",
        "agemys.org/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "一周更新 - AGE动漫 - Powered by RSSHub",
      "errorAt": "2025-10-17T11:01:59.581Z",
      "errorMessage": "[GET] \"https://www.agemys.org/update\": <no response> fetch failed (certificate has expired)\nAuthentication failed. Access denied.\n/agefans/update\n[GET] \"https://www.agemys.org/update\": <no response> fetch failed\n[GET] \"https://www.agemys.org/update\": <no response> fetch failed (certificate has expired)\n",
      "id": "59083231915003932",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.agemys.org/update",
      "title": "一周更新 - AGE动漫",
      "type": "feed",
      "url": "rsshub://agefans/update"
    }
  ],
  "url": "agemys.org/update"
}
```
