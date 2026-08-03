# Polymarket - User Positions

## Coverage
`index-only`

## Route
- Namespace: `polymarket`
- Namespace Name: `Polymarket`
- Route Path: `/polymarket/positions/:address`
- Route Name: `User Positions`
- Example: `/polymarket/positions/0x7c3db723f1d4d8cb9c550095203b686cb11e5c6b`
- URL: `polymarket.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `heqi201255`
- Source Location: `positions.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `address`: Wallet address (0x...)


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
    "finance"
  ],
  "example": "/polymarket/positions/0x7c3db723f1d4d8cb9c550095203b686cb11e5c6b",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "positions.ts",
  "maintainers": [
    "heqi201255"
  ],
  "name": "User Positions",
  "parameters": {
    "address": "Wallet address (0x...)"
  },
  "path": "/positions/:address",
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(1) ] to not include 'https://polymarket.com/event/presiden…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "polymarket.com"
}
```
