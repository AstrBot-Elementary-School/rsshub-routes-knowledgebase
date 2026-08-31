# Mirror - User

## Coverage
`index-only`

## Route
- Namespace: `mirror`
- Namespace Name: `Mirror`
- Route Path: `/mirror/:id`
- Route Name: `User`
- Example: `/mirror/tingfei.eth`
- URL: `mirror.xyz`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `fifteen42, rde9, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: user id


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
    "new-media"
  ],
  "example": "/mirror/tingfei.eth",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 24,
  "location": "index.ts",
  "maintainers": [
    "fifteen42",
    "rde9",
    "nczitzk"
  ],
  "name": "User",
  "parameters": {
    "id": "user id"
  },
  "path": "/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "1kx is a crypto investment firm that specializes in ecosystem growth. - Powered by RSSHub",
      "errorAt": "2025-07-20T17:41:15.723Z",
      "errorMessage": "[GET] \"https://mirror.xyz/1kx.eth\": 403 Forbidden\n",
      "id": "41477723842378786",
      "image": "https://images.mirror-media.xyz/publication-images/1FwtVSORzEXfclP8xyoED.png?height=400&width=400",
      "ownerUserId": null,
      "siteUrl": "https://mirror.xyz/1kx.eth",
      "title": "1kx - Mirror",
      "type": "feed",
      "url": "rsshub://mirror/1kx.eth"
    },
    {
      "description": "tingfei - Mirror - Powered by RSSHub",
      "errorAt": "2025-07-20T18:18:22.556Z",
      "errorMessage": "[GET] \"https://mirror.xyz/tingfei.eth\": 403 Forbidden\n",
      "id": "83068440830803968",
      "image": "https://images.mirror-media.xyz/publication-images/exbc77pKezAGWfkt-mTQs.png?height=300&width=300",
      "ownerUserId": null,
      "siteUrl": "https://mirror.xyz/tingfei.eth",
      "title": "tingfei - Mirror",
      "type": "feed",
      "url": "rsshub://mirror/tingfei.eth"
    }
  ]
}
```
