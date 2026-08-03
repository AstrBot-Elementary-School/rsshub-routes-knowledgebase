# ELSEVIER - Special Issue

## Coverage
`index-only`

## Route
- Namespace: `elsevier`
- Namespace Name: `ELSEVIER`
- Route Path: `/elsevier/:journal/:issue`
- Route Name: `Special Issue`
- Example: `/elsevier/signal-processing/192`
- URL: `www.sciencedirect.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `Derekmini, sunwolf-swb`
- Source Location: `issue.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `journal`: Journal Name, the part of the URL after `/journal/`
- `issue`: Release Number, the number in the URL after `/vol/` (If both Volume and Issue exist, must use the `Volume-Issue` form, e.g., `/elsevier/aace-clinical-case-reports/7-6`)


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sciencedirect.com/journal/:journal/vol/:issue`
- `target`: `/:journal/:issue`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/elsevier/signal-processing/192",
  "heat": 0,
  "location": "issue.ts",
  "maintainers": [
    "Derekmini",
    "sunwolf-swb"
  ],
  "name": "Special Issue",
  "parameters": {
    "issue": "Release Number, the number in the URL after `/vol/` (If both Volume and Issue exist, must use the `Volume-Issue` form, e.g., `/elsevier/aace-clinical-case-reports/7-6`)",
    "journal": "Journal Name, the part of the URL after `/journal/`"
  },
  "path": "/:journal/:issue",
  "radar": [
    {
      "source": [
        "www.sciencedirect.com/journal/:journal/vol/:issue"
      ],
      "target": "/:journal/:issue"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
