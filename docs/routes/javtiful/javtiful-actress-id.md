# Javtiful - Actress

## Coverage
`index-only`

## Route
- Namespace: `javtiful`
- Namespace Name: `Javtiful`
- Route Path: `/javtiful/actress/:id`
- Route Name: `Actress`
- Example: `/javtiful/actress/akari-tsumugi`
- URL: `javtiful.com`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `huanfe1`
- Source Location: `actress.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Actress name


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `javtiful.com/actress/:id`
  - `javtiful.com/actress/:id/*`
- `target`: `/actress/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia",
    "popular"
  ],
  "example": "/javtiful/actress/akari-tsumugi",
  "features": {
    "nsfw": true
  },
  "heat": 12203,
  "location": "actress.ts",
  "maintainers": [
    "huanfe1"
  ],
  "name": "Actress",
  "parameters": {
    "id": "Actress name"
  },
  "path": "/actress/:id",
  "radar": [
    {
      "source": [
        "javtiful.com/actress/:id",
        "javtiful.com/actress/:id/*"
      ],
      "target": "/actress/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 'RSSHub' not to be 'RSSHub' // Object.is equality\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:72:30)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:109:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Mikami Yua - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75560870348182528",
      "image": "/uploads/uploads/collections/actresses/2026/04/27/ecc150ff8778706120aa68e0d3997872.jpg",
      "ownerUserId": null,
      "siteUrl": "https://javtiful.com/actress/mikami-yua",
      "title": "Mikami Yua",
      "type": "feed",
      "url": "rsshub://javtiful/actress/mikami-yua"
    },
    {
      "description": "Akari Tsumugi - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63617818932634624",
      "image": "/uploads/uploads/collections/actresses/2026/04/27/09de335a007187a2ccfb69269920102a.jpg",
      "ownerUserId": null,
      "siteUrl": "https://javtiful.com/actress/akari-tsumugi",
      "title": "Akari Tsumugi",
      "type": "feed",
      "url": "rsshub://javtiful/actress/akari-tsumugi"
    }
  ]
}
```
