# American Economic Association - Journal

## Coverage
`index-only`

## Route
- Namespace: `aeaweb`
- Namespace Name: `American Economic Association`
- Route Path: `/aeaweb/:id`
- Route Name: `Journal`
- Example: `/aeaweb/aer`
- URL: `aeaweb.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
The URL of the journal [American Economic Review](https://www.aeaweb.org/journals/aer) is `https://www.aeaweb.org/journals/aer`, where `aer` is the id of the journal, so the route for this journal is `/aeaweb/aer`.

::: tip
More jounals can be found in [AEA Journals](https://www.aeaweb.org/journals).
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
  - `aeaweb.org/journals/:id`
  - `aeaweb.org/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "The URL of the journal [American Economic Review](https://www.aeaweb.org/journals/aer) is `https://www.aeaweb.org/journals/aer`, where `aer` is the id of the journal, so the route for this journal is `/aeaweb/aer`.\n\n::: tip\nMore jounals can be found in [AEA Journals](https://www.aeaweb.org/journals).\n:::",
  "example": "/aeaweb/aer",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "heat": 265,
  "location": "index.tsx",
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
        "aeaweb.org/journals/:id",
        "aeaweb.org/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 'RSSHub' not to be 'RSSHub' // Object.is equality\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:69:30)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "The American Economic Review (AER) is a general-interest economics journal. Established in 1911, the AER is among the nation's oldest and most respected scholarly journals in economics. The journal publishes 12 issues per year containing articles on a broad range of topics. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67194781357752320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.aeaweb.org/journals/aer",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://aeaweb/aer"
    },
    {
      "description": "American Economic Journal: Applied Economics covers a range of topics in applied economics, with a focus on empirical microeconomic issues. Subject areas include labor economics, development microeconomics, health, education, demography, empirical corporate finance, empirical studies of trade, and empirical behavioral economics. The journal publishes four issues per year. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75182460564086784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.aeaweb.org/journals/app",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://aeaweb/app"
    }
  ]
}
```
