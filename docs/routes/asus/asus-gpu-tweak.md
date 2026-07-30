# ASUS - GPU Tweak

## Coverage
`index-only`

## Route
- Namespace: `asus`
- Namespace Name: `ASUS`
- Route Path: `/asus/gpu-tweak`
- Route Name: `GPU Tweak`
- Example: `/asus/gpu-tweak`
- URL: `asus.com/campaign/GPU-Tweak-III/*`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `gpu-tweak.ts`
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
  - `asus.com/campaign/GPU-Tweak-III/*`
  - `asus.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/asus/gpu-tweak",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "gpu-tweak.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "GPU Tweak",
  "parameters": {},
  "path": "/gpu-tweak",
  "radar": [
    {
      "source": [
        "asus.com/campaign/GPU-Tweak-III/*",
        "asus.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(1) ] to not include 'https://dlcdnets.asus.com/pub/ASUS/Gr…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "asus.com/campaign/GPU-Tweak-III/*"
}
```
