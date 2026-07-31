# 川流 - 严选

## Coverage
`index-only`

## Route
- Namespace: `chuanliu`
- Namespace Name: `川流`
- Route Path: `/chuanliu/nice`
- Route Name: `严选`
- Example: `/chuanliu/nice`
- URL: `chuanliu.org/nice`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `nczitzk`
- Source Location: `nice.tsx`
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
  - `chuanliu.org/nice`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/chuanliu/nice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "nice.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "严选",
  "parameters": {},
  "path": "/nice",
  "radar": [
    {
      "source": [
        "chuanliu.org/nice"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-08T11:05:15.343Z",
      "errorMessage": "[GET] \"https://s.chuanliu.org/api/dis/api/v1/memo?creatorId=1&offset=0&limit=100\": <no response> fetch failed (getaddrinfo ENOTFOUND s.chuanliu.org)\n",
      "id": "154479685635981324",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://chuanliu/nice"
    }
  ],
  "url": "chuanliu.org/nice"
}
```
