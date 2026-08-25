# CoStar - Press Releases

## Coverage
`index-only`

## Route
- Namespace: `costar`
- Namespace Name: `CoStar`
- Route Path: `/costar/press-releases/:filter{.+}?`
- Route Name: `Press Releases`
- Example: `/costar/press-releases`
- URL: `www.costar.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `press-releases.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Press Releases - Asia Pacific - Preliminary](https://www.costar.com/products/benchmark/resources/press-releases?region=406\&tag=581), where the source URL is `https://www.costar.com/products/benchmark/resources/press-releases?region=406&tag=581`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/costar/press-releases/region=406&tag=581`](https://rsshub.app/costar/press-releases/region=406\&tag=581).
:::

## Parameters
- `filter`: {"description": "Filter"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.costar.com`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nTo subscribe to [Press Releases - Asia Pacific - Preliminary](https://www.costar.com/products/benchmark/resources/press-releases?region=406\\&tag=581), where the source URL is `https://www.costar.com/products/benchmark/resources/press-releases?region=406&tag=581`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/costar/press-releases/region=406&tag=581`](https://rsshub.app/costar/press-releases/region=406\\&tag=581).\n:::",
  "example": "/costar/press-releases",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "press-releases.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Press Releases",
  "parameters": {
    "filter": {
      "description": "Filter"
    }
  },
  "path": "/press-releases/:filter{.+}?",
  "radar": [
    {
      "source": [
        "www.costar.com"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.costar.com",
  "view": 0
}
```
