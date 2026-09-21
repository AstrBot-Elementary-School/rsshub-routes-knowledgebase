# iri-search - 新着物件

## Coverage
`index-only`

## Route
- Namespace: `iri-search`
- Namespace Name: `iri-search`
- Route Path: `/iri-search/estate/:area?`
- Route Name: `新着物件`
- Example: `/iri-search/estate/tokyo`
- URL: `www.iri-search.net`
- Language: `_None_`
- Categories: `other`
- Maintainers: `pseudoyu`
- Source Location: `estate.ts`
- Source Module: `_None_`

## Description
New listings on 居抜き物件検索 iri-search sorted by 新着順 (first page, 30 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，保証金・敷金，居抜き譲渡代，以前の業態，業種可否，掲載日，…) parsed from the list and detail pages; unknown values are `null`.

| Query   | Description                                                                  | Default |
| ------- | ---------------------------------------------------------------------------- | ------- |
| `limit` | Number of listings to process (detail pages are fetched per listing), max 30 | 30      |

## Parameters
- `area`: Region slug (shutoken, hokkaido, tohoku, kitakanto, hokuriku, koshinetsu, tokai, kinki, chugoku, shikoku, kyushu, okinawa) or a 首都圏 prefecture (tokyo, kanagawa, saitama, chiba or its JIS code); omit for nationwide


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.iri-search.net/estate_search`
  - `www.iri-search.net/`
- `target`: `/estate`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "New listings on 居抜き物件検索 iri-search sorted by 新着順 (first page, 30 listings). Each item's `_extra` carries the structured listing fields (賃料，坪，坪単価，階，最寄駅，保証金・敷金，居抜き譲渡代，以前の業態，業種可否，掲載日，…) parsed from the list and detail pages; unknown values are `null`.\n\n| Query   | Description                                                                  | Default |\n| ------- | ---------------------------------------------------------------------------- | ------- |\n| `limit` | Number of listings to process (detail pages are fetched per listing), max 30 | 30      |",
  "example": "/iri-search/estate/tokyo",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportRadar": true
  },
  "heat": 0,
  "location": "estate.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "name": "新着物件",
  "parameters": {
    "area": "Region slug (shutoken, hokkaido, tohoku, kitakanto, hokuriku, koshinetsu, tokai, kinki, chugoku, shikoku, kyushu, okinawa) or a 首都圏 prefecture (tokyo, kanagawa, saitama, chiba or its JIS code); omit for nationwide"
  },
  "path": "/estate/:area?",
  "radar": [
    {
      "source": [
        "www.iri-search.net/estate_search",
        "www.iri-search.net/"
      ],
      "target": "/estate"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [],
  "url": "www.iri-search.net"
}
```
