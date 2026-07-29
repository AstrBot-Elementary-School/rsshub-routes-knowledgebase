# TokenInsight - Research

## Coverage
`index-only`

## Route
- Namespace: `tokeninsight`
- Namespace Name: `TokenInsight`
- Route Path: `/tokeninsight/report/:lang?`
- Route Name: `Research`
- Example: `/tokeninsight/report/en`
- URL: `tokeninsight.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `fuergaosi233`
- Source Location: `report.ts`
- Source Module: `_None_`

## Description
Language:

| Chinese | English |
| ------- | ------- |
| zh      | en      |

## Parameters
- `lang`: Language, see below, Chinese by default


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
  - `tokeninsight.com/:lang/report`
- `target`: `/report/:lang`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Language:\n\n| Chinese | English |\n| ------- | ------- |\n| zh      | en      |",
  "example": "/tokeninsight/report/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "report.ts",
  "maintainers": [
    "fuergaosi233"
  ],
  "name": "Research",
  "parameters": {
    "lang": "Language, see below, Chinese by default"
  },
  "path": "/report/:lang?",
  "radar": [
    {
      "source": [
        "tokeninsight.com/:lang/report"
      ],
      "target": "/report/:lang"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-26T04:23:55.172Z",
      "errorMessage": "[POST] \"https://www.tokeninsight.com/api/user/search/getAllList\": 403 Forbidden\n",
      "id": "149642094386478102",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://tokeninsight/report/zh"
    }
  ]
}
```
