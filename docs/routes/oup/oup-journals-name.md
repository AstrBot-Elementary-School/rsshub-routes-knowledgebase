# Oxford University Press - Oxford Academic - Journal

## Coverage
`index-only`

## Route
- Namespace: `oup`
- Namespace Name: `Oxford University Press`
- Route Path: `/oup/journals/:name`
- Route Name: `Oxford Academic - Journal`
- Example: `/oup/journals/adaptation`
- URL: `academic.oup.com/`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `Fatpandac`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: short name for a journal, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `academic.oup.com/`
  - `academic.oup.com/:name/issue`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/oup/journals/adaptation",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 47,
  "location": "index.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "Oxford Academic - Journal",
  "parameters": {
    "name": "short name for a journal, can be found in URL"
  },
  "path": "/journals/:name",
  "radar": [
    {
      "source": [
        "academic.oup.com/",
        "academic.oup.com/:name/issue"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "OUP - qje - Powered by RSSHub",
      "errorAt": "2025-07-18T11:52:23.943Z",
      "errorMessage": "[GET] \"https://academic.oup.com/qje/issue\": 403 Forbidden\n",
      "id": "73541899125060608",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://academic.oup.com/qje/issue",
      "title": "OUP - qje",
      "type": "feed",
      "url": "rsshub://oup/journals/qje"
    },
    {
      "description": "OUP - restud - Powered by RSSHub",
      "errorAt": "2025-07-18T14:31:43.383Z",
      "errorMessage": "[GET] \"https://academic.oup.com/restud/issue\": 403 \n",
      "id": "73543481897669632",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://academic.oup.com/restud/issue",
      "title": "OUP - restud",
      "type": "feed",
      "url": "rsshub://oup/journals/restud"
    }
  ],
  "url": "academic.oup.com/"
}
```
