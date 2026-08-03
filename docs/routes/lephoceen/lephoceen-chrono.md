# Le Phocéen - Fil Info Le Phocéen (Chrono)

## Coverage
`index-only`

## Route
- Namespace: `lephoceen`
- Namespace Name: `Le Phocéen`
- Route Path: `/lephoceen/chrono`
- Route Name: `Fil Info Le Phocéen (Chrono)`
- Example: `/lephoceen/chrono`
- URL: `lephoceen.fr`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `Loopy03`
- Source Location: `chrono.ts`
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
  - `lephoceen.fr/chrono`
- `target`: `/chrono`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "example": "/lephoceen/chrono",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "chrono.ts",
  "maintainers": [
    "Loopy03"
  ],
  "name": "Fil Info Le Phocéen (Chrono)",
  "parameters": {},
  "path": "/chrono",
  "radar": [
    {
      "source": [
        "lephoceen.fr/chrono"
      ],
      "target": "/chrono"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(4) ] to not include 'https://www.lephoceen.fr/infos-om/aut…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
