# Polymarket - Event

## Coverage
`index-only`

## Route
- Namespace: `polymarket`
- Namespace Name: `Polymarket`
- Route Path: `/polymarket/event/:slug`
- Route Name: `Event`
- Example: `/polymarket/event/presidential-election-winner-2024`
- URL: `polymarket.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `heqi201255`
- Source Location: `event.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `slug`: Event slug from the URL (e.g. presidential-election-winner-2024)


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
  - `polymarket.com/event/:slug`
- `target`: `/event/:slug`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/polymarket/event/presidential-election-winner-2024",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "event.ts",
  "maintainers": [
    "heqi201255"
  ],
  "name": "Event",
  "parameters": {
    "slug": "Event slug from the URL (e.g. presidential-election-winner-2024)"
  },
  "path": "/event/:slug",
  "radar": [
    {
      "source": [
        "polymarket.com/event/:slug"
      ],
      "target": "/event/:slug"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(1) ] to not include 'https://polymarket.com/event/presiden…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "polymarket.com"
}
```
