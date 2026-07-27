# Deepin - BBS Home Page

## Coverage
`index-only`

## Route
- Namespace: `deepin`
- Namespace Name: `Deepin`
- Route Path: `/deepin/homepage/:user_id`
- Route Name: `BBS Home Page`
- Example: `/deepin/homepage/78326`
- URL: `bbs.deepin.org`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `tensor-tech`
- Source Location: `homepage.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user_id`: user id


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `bbs.deepin.org/user/:user_id`
- `target`: `/homepage/:user_id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/deepin/homepage/78326",
  "heat": 2,
  "location": "homepage.ts",
  "maintainers": [
    "tensor-tech"
  ],
  "name": "BBS Home Page",
  "parameters": {
    "user_id": "user id"
  },
  "path": "/homepage/:user_id",
  "radar": [
    {
      "source": [
        "bbs.deepin.org/user/:user_id"
      ],
      "target": "/homepage/:user_id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "广雅居士/deepin论坛主页 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63580812692062208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bbs.deepin.org/user/78326",
      "title": "广雅居士/deepin论坛主页",
      "type": "feed",
      "url": "rsshub://deepin/homepage/78326"
    }
  ]
}
```
