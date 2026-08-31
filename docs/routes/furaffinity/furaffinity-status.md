# Furaffinity - Status

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/furaffinity/status`
- Route Name: `Status`
- Example: `/furaffinity/status`
- URL: `furaffinity.net`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `status.ts`
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
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `furaffinity.net`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/furaffinity/status",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "status.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "name": "Status",
  "parameters": {},
  "path": "/status",
  "radar": [
    {
      "source": [
        "furaffinity.net"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Fur Affinity Status - Powered by RSSHub",
      "errorAt": "2026-05-25T12:32:54.917Z",
      "errorMessage": "[GET] \"https://faexport.spangle.org.uk/status.json\": 500 Internal Server Error\n",
      "id": "87385847063373824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.furaffinity.net/",
      "title": "Fur Affinity | Status",
      "type": "feed",
      "url": "rsshub://furaffinity/status"
    }
  ],
  "url": "furaffinity.net"
}
```
