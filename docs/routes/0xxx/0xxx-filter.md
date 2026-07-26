# 0xxx.ws - Source

## Coverage
`index-only`

## Route
- Namespace: `0xxx`
- Namespace Name: `0xxx.ws`
- Route Path: `/0xxx/:filter?`
- Route Name: `Source`
- Example: `/0xxx/category=Movie-HD-1080p`
- URL: `0xxx.ws`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
To subscribe to [Movie HD 1080p](https://0xxx.ws?category=Movie-HD-1080p), where the source URL is `https://0xxx.ws?category=Movie-HD-1080p`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/0xxx/category=Movie-HD-1080p`](https://rsshub.app/0xxx/category=Movie-HD-1080p).
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
- `nfsw`: true

## Radar
### Rule 1
- `source`:
  - `0xxx.ws`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\nTo subscribe to [Movie HD 1080p](https://0xxx.ws?category=Movie-HD-1080p), where the source URL is `https://0xxx.ws?category=Movie-HD-1080p`, extract the certain parts from this URL to be used as parameters, resulting in the route as [`/0xxx/category=Movie-HD-1080p`](https://rsshub.app/0xxx/category=Movie-HD-1080p).\n:::",
  "example": "/0xxx/category=Movie-HD-1080p",
  "features": {
    "antiCrawler": false,
    "nfsw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 22,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Source",
  "parameters": {
    "filter": {
      "description": "Filter"
    }
  },
  "path": "/:filter?",
  "radar": [
    {
      "source": [
        "0xxx.ws"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "Latest high quality 0day porn available for free download. Home of scene and P2P releases - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "197857223398767616",
      "image": "https://0xxx.ws/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://0xxx.ws/?catalogue=Blacked",
      "title": "0xxx.ws - catalogue=Blacked",
      "type": "feed",
      "url": "rsshub://0xxx/catalogue%3DBlacked"
    },
    {
      "description": "Latest high quality 0day porn available for free download. Home of scene and P2P releases - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "196817673683011584",
      "image": "https://0xxx.ws/images/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://0xxx.ws/",
      "title": "0xxx.ws - undefined",
      "type": "feed",
      "url": "rsshub://0xxx"
    }
  ],
  "url": "0xxx.ws",
  "view": 0
}
```
