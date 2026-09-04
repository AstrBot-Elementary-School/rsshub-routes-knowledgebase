# Springer - Journal

## Coverage
`index-only`

## Route
- Namespace: `springer`
- Namespace Name: `Springer`
- Route Path: `/springer/journal/:journal`
- Route Name: `Journal`
- Example: `/springer/journal/10450`
- URL: `www.springer.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `Derekmini, TonyRL, xiahaoyun`
- Source Location: `journal.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `journal`: Journal Code, the number in the URL from the journal homepage


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
  - `www.springer.com/journal/:journal/*`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/springer/journal/10450",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 164,
  "location": "journal.tsx",
  "maintainers": [
    "Derekmini",
    "TonyRL",
    "xiahaoyun"
  ],
  "name": "Journal",
  "parameters": {
    "journal": "Journal Code, the number in the URL from the journal homepage"
  },
  "path": "/journal/:journal",
  "radar": [
    {
      "source": [
        "www.springer.com/journal/:journal/*"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Virtual Reality - Powered by RSSHub",
      "errorAt": "2026-02-03T17:46:17.963Z",
      "errorMessage": "[GET] \"https://link.springer.comundefined\": <no response> fetch failed\n[GET] \"https://link.springer.comundefined\": <no response> fetch failed (getaddrinfo ENOTFOUND link.springer.comundefined)\n",
      "id": "70715894280141824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://link.springer.com/journal/10055/volumes-and-issues",
      "title": "Virtual Reality",
      "type": "feed",
      "url": "rsshub://springer/journal/10055"
    },
    {
      "description": "Journal of Happiness Studies - Powered by RSSHub",
      "errorAt": "2026-02-03T16:31:01.622Z",
      "errorMessage": "[GET] \"https://link.springer.comundefined\": <no response> fetch failed (getaddrinfo ENOTFOUND link.springer.comundefined)\n",
      "id": "42411432461774848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://link.springer.com/journal/10902/volumes-and-issues",
      "title": "Journal of Happiness Studies",
      "type": "feed",
      "url": "rsshub://springer/journal/10902"
    }
  ]
}
```
