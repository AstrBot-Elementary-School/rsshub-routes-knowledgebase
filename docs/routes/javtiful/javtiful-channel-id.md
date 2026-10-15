# Javtiful - Channel

## Coverage
`index-only`

## Route
- Namespace: `javtiful`
- Namespace Name: `Javtiful`
- Route Path: `/javtiful/channel/:id`
- Route Name: `Channel`
- Example: `/javtiful/channel/madonna`
- URL: `javtiful.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `huanfe1`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Channel name


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `javtiful.com/channel/:id`
  - `javtiful.com/channel/:id/*`
- `target`: `/channel/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/javtiful/channel/madonna",
  "features": {
    "nsfw": true
  },
  "heat": 501,
  "location": "channel.ts",
  "maintainers": [
    "huanfe1"
  ],
  "name": "Channel",
  "parameters": {
    "id": "Channel name"
  },
  "path": "/channel/:id",
  "radar": [
    {
      "source": [
        "javtiful.com/channel/:id",
        "javtiful.com/channel/:id/*"
      ],
      "target": "/channel/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 'RSSHub' not to be 'RSSHub' // Object.is equality\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:72:30)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:109:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "FC2PPV - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66507508116600832",
      "image": "/uploads/uploads/collections/channels/2026/04/27/7aded8ab71998f38edf0f671211d728a.jpg",
      "ownerUserId": null,
      "siteUrl": "https://javtiful.com/channel/FC2PPV",
      "title": "FC2PPV",
      "type": "feed",
      "url": "rsshub://javtiful/channel/FC2PPV"
    },
    {
      "description": "Madonna - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63624830978450432",
      "image": "/uploads/uploads/collections/channels/2026/04/27/4b087639fa1a1a63db886b3b87bf6784.jpg",
      "ownerUserId": null,
      "siteUrl": "https://javtiful.com/channel/madonna",
      "title": "Madonna",
      "type": "feed",
      "url": "rsshub://javtiful/channel/madonna"
    }
  ]
}
```
