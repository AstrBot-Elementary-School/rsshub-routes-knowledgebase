# Farcaster - Farcaster User

## Coverage
`index-only`

## Route
- Namespace: `farcaster`
- Namespace Name: `Farcaster`
- Route Path: `/farcaster/user/:username`
- Route Name: `Farcaster User`
- Example: `/farcaster/user/vitalik.eth`
- URL: `www.farcaster.xyz`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `username`: Farcaster username


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
  - `warpcast.com/:username`
- `target`: `/user/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/farcaster/user/vitalik.eth",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "user.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Farcaster User",
  "parameters": {
    "username": "Farcaster username"
  },
  "path": "/user/:username",
  "radar": [
    {
      "source": [
        "warpcast.com/:username"
      ],
      "target": "/user/:username"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Vitalik Buterin on Farcaster - Powered by RSSHub",
      "errorAt": "2026-01-29T21:57:38.280Z",
      "errorMessage": "[GET] \"https://client.warpcast.com/v2/casts?fid=5650&limit=100\": 400 Bad Request\n",
      "id": "143719820510416896",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://warpcast.com/vitalik.eth",
      "title": "Vitalik Buterin on Farcaster",
      "type": "feed",
      "url": "rsshub://farcaster/user/vitalik.eth"
    }
  ]
}
```
