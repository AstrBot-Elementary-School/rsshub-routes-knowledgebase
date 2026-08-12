# Annual Reviews - Journal

## Coverage
`index-only`

## Route
- Namespace: `annualreviews`
- Namespace Name: `Annual Reviews`
- Route Path: `/annualreviews/:id`
- Route Name: `Journal`
- Example: `/annualreviews/anchem`
- URL: `annualreviews.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
The URL of the journal [Annual Review of Analytical Chemistry](https://www.annualreviews.org/journal/anchem) is `https://www.annualreviews.org/journal/anchem`, where `anchem` is the id of the journal, so the route for this journal is `/annualreviews/anchem`.

::: tip
More jounals can be found in [Browse Journals](https://www.annualreviews.org/action/showPublications).
:::

## Parameters
- `id`: Journal id, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `annualreviews.org/journal/:id`
  - `annualreviews.org/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "The URL of the journal [Annual Review of Analytical Chemistry](https://www.annualreviews.org/journal/anchem) is `https://www.annualreviews.org/journal/anchem`, where `anchem` is the id of the journal, so the route for this journal is `/annualreviews/anchem`.\n\n::: tip\nMore jounals can be found in [Browse Journals](https://www.annualreviews.org/action/showPublications).\n:::",
  "example": "/annualreviews/anchem",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "heat": 5,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Journal",
  "parameters": {
    "id": "Journal id, can be found in URL"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "annualreviews.org/journal/:id",
        "annualreviews.org/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2026-06-30T06:04:40.784Z",
      "errorMessage": "[GET] \"https://www.annualreviews.org/r/conmatphys_rss\": 403 Forbidden\n",
      "id": "1178645011650969607",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://annualreviews/conmatphys"
    },
    {
      "description": null,
      "errorAt": "2026-06-30T06:04:20.800Z",
      "errorMessage": "[GET] \"https://www.annualreviews.org/r/matsci_rss\": 403 Forbidden\n",
      "id": "1178645011650969608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://annualreviews/matsci"
    }
  ]
}
```
