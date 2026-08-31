# HyperDash - Top Traders

## Coverage
`index-only`

## Route
- Namespace: `hyperdash`
- Namespace Name: `HyperDash`
- Route Path: `/hyperdash/top-traders`
- Route Name: `Top Traders`
- Example: `/hyperdash/top-traders`
- URL: `hyperdash.info`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `top-traders.tsx`
- Source Module: `_None_`

## Description
Get the latest top traders data from HyperDash

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
  - `hyperdash.info/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Get the latest top traders data from HyperDash",
  "example": "/hyperdash/top-traders",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "top-traders.tsx",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "Top Traders",
  "parameters": {},
  "path": "/top-traders",
  "radar": [
    {
      "source": [
        "hyperdash.info/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Top performing traders on HyperDash - real-time cryptocurrency derivatives trading analytics - Powered by RSSHub",
      "errorAt": "2025-11-18T23:30:05.578Z",
      "errorMessage": "[GET] \"https://hyperdash.info/api/hyperdash/top-traders-cached\": 403 Forbidden\n",
      "id": "157372456699561984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hyperdash.info/",
      "title": "HyperDash Top Traders",
      "type": "feed",
      "url": "rsshub://hyperdash/top-traders"
    }
  ]
}
```
