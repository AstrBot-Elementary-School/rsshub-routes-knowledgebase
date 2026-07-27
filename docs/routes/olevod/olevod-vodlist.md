# 欧乐影院 - 最新视频

## Coverage
`index-only`

## Route
- Namespace: `olevod`
- Namespace Name: `欧乐影院`
- Route Path: `/olevod/vodlist`
- Route Name: `最新视频`
- Example: `/olevod/vodlist`
- URL: `olevod.one`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `fang63625`
- Source Location: `vodlist.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.olevod.one`
- `target`: `/vodlist`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/olevod/vodlist",
  "features": {
    "nsfw": true
  },
  "heat": 127,
  "location": "vodlist.ts",
  "maintainers": [
    "fang63625"
  ],
  "name": "最新视频",
  "path": "/vodlist",
  "radar": [
    {
      "source": [
        "www.olevod.one"
      ],
      "target": "/vodlist"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(30) ] to not include 'https://www.olevod.one/vod/202620632'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "欧乐影院 最新视频 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "129729686508788736",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.olevod.one/",
      "title": "欧乐影院 最新视频",
      "type": "feed",
      "url": "rsshub://olevod/vodlist"
    }
  ]
}
```
