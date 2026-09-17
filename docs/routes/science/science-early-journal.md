# Science Magazine - First Release

## Coverage
`index-only`

## Route
- Namespace: `science`
- Namespace Name: `Science Magazine`
- Route Path: `/science/early/:journal?`
- Route Name: `First Release`
- Example: `/science/early`
- URL: `science.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `early.ts`
- Source Module: `_None_`

## Description
*only Science, Science Immunology and Science Translational Medicine have first release*

## Parameters
- `journal`: Short name for a journal


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `science.org/journal/:journal`
  - `science.org/toc/:journal/0/0`
- `target`: `/early/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "*only Science, Science Immunology and Science Translational Medicine have first release*",
  "example": "/science/early",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "heat": 17,
  "location": "early.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "name": "First Release",
  "parameters": {
    "journal": "Short name for a journal"
  },
  "path": "/early/:journal?",
  "radar": [
    {
      "source": [
        "science.org/journal/:journal",
        "science.org/toc/:journal/0/0"
      ],
      "target": "/early/:journal"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-01T11:07:38.022Z",
      "errorMessage": "[GET] \"https://www.science.org/toc/science/0/0\": 403 Forbidden\n",
      "id": "151955931879114756",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://science/early"
    },
    {
      "description": null,
      "errorAt": "2026-06-30T06:04:30.952Z",
      "errorMessage": "[GET] \"https://www.science.org/toc/science/0/0\": 403 Forbidden\n",
      "id": "1178645011650969611",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://science/early/science"
    }
  ]
}
```
