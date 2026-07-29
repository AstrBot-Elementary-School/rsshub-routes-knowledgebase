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
  "topFeeds": []
}
```
