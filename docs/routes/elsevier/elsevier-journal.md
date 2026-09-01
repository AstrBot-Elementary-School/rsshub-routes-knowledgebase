# ELSEVIER - Journal

## Coverage
`index-only`

## Route
- Namespace: `elsevier`
- Namespace Name: `ELSEVIER`
- Route Path: `/elsevier/:journal`
- Route Name: `Journal`
- Example: `/elsevier/signal-processing`
- URL: `www.sciencedirect.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `Derekmini, sunwolf-swb`
- Source Location: `journal.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `journal`: Journal Name, the part of the URL after `/journal/`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sciencedirect.com/journal/:journal/*`
- `target`: `/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/elsevier/signal-processing",
  "heat": 3,
  "location": "journal.ts",
  "maintainers": [
    "Derekmini",
    "sunwolf-swb"
  ],
  "name": "Journal",
  "parameters": {
    "journal": "Journal Name, the part of the URL after `/journal/`"
  },
  "path": "/:journal",
  "radar": [
    {
      "source": [
        "www.sciencedirect.com/journal/:journal/*"
      ],
      "target": "/:journal"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-08-03T12:39:01.065Z",
      "errorMessage": "[GET] \"https://www.sciencedirect.com/journal/computers-and-security\": 400 Bad Request\n",
      "id": "174810629543869442",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://elsevier/computers-and-security"
    },
    {
      "description": null,
      "errorAt": "2025-06-01T07:54:11.221Z",
      "errorMessage": "[GET] \"https://www.sciencedirect.com/journal/journal-of-functional-analysis\": 403 Forbidden\n",
      "id": "151906373171554304",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://elsevier/journal-of-functional-analysis"
    }
  ]
}
```
