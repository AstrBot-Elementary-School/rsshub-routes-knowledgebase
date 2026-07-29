# China University of Geosciences (Beijing) - 教务处

## Coverage
`index-only`

## Route
- Namespace: `cugb`
- Namespace Name: `China University of Geosciences (Beijing)`
- Route Path: `/cugb/jwc/:channel?`
- Route Name: `教务处`
- Example: `/cugb/jwc/xszq`
- URL: `cugb.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `syncmeta`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `channel`: 栏目，默认为 `xszq` 学生专区


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
  - `jwc.cugb.edu.cn/:channel`
- `target`: `/jwc/:channel`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cugb/jwc/xszq",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "syncmeta"
  ],
  "name": "教务处",
  "parameters": {
    "channel": "栏目，默认为 `xszq` 学生专区"
  },
  "path": "/jwc/:channel?",
  "radar": [
    {
      "source": [
        "jwc.cugb.edu.cn/:channel"
      ],
      "target": "/jwc/:channel"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
