# Monster Hunter - World: Iceborne 最新消息

## Coverage
`index-only`

## Route
- Namespace: `monsterhunter`
- Namespace Name: `Monster Hunter`
- Route Path: `/monsterhunter/world-iceborne/news`
- Route Name: `World: Iceborne 最新消息`
- Example: `/monsterhunter/world-iceborne/news`
- URL: `www.monsterhunter.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `DIYgod`
- Source Location: `world-iceborne-news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.monsterhunter.com/`
  - `www.monsterhunter.com/*path`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/monsterhunter/world-iceborne/news",
  "heat": 0,
  "location": "world-iceborne-news.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "World: Iceborne 最新消息",
  "path": "/world-iceborne/news",
  "radar": [
    {
      "source": [
        "www.monsterhunter.com/",
        "www.monsterhunter.com/*path"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(20) ] to not include 'https://www.monsterhunter.com/world-i…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
