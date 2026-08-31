# Público - Internacional

## Coverage
`index-only`

## Route
- Namespace: `publico`
- Namespace Name: `Público`
- Route Path: `/publico/internacional/:subsection?`
- Route Name: `Internacional`
- Example: `/publico/internacional`
- URL: `publico.es`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `adrianrico97`
- Source Location: `internacional.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `subsection`: {"description": "Filter by subsection. Check the subsections available on the newspaper's website."}


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `publico.es/internacional`
- `target`: `/internacional`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/publico/internacional",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "internacional.ts",
  "maintainers": [
    "adrianrico97"
  ],
  "name": "Internacional",
  "parameters": {
    "subsection": {
      "description": "Filter by subsection. Check the subsections available on the newspaper's website."
    }
  },
  "path": "/internacional/:subsection?",
  "radar": [
    {
      "source": [
        "publico.es/internacional"
      ],
      "target": "/internacional"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected { '$': { isPermaLink: 'false' } } to deeply equal Any<String>\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:84:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Internacional | Público - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "129920522272080896",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.publico.es/internacional",
      "title": "Internacional | Público",
      "type": "feed",
      "url": "rsshub://publico/internacional"
    }
  ]
}
```
