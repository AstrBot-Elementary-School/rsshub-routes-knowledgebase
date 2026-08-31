# ATP Tour - News

## Coverage
`index-only`

## Route
- Namespace: `atptour`
- Namespace Name: `ATP Tour`
- Route Path: `/atptour/news/:lang?`
- Route Name: `News`
- Example: `/atptour/news/en`
- URL: `www.atptour.com`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `LM1207`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: en or es.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `atptour.com`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "example": "/atptour/news/en",
  "heat": 1,
  "location": "news.ts",
  "maintainers": [
    "LM1207"
  ],
  "name": "News",
  "parameters": {
    "lang": "en or es."
  },
  "path": "/news/:lang?",
  "radar": [
    {
      "source": [
        "atptour.com"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "News from the official site of men's professional tennis. - Powered by RSSHub",
      "errorAt": "2026-05-06T10:58:41.651Z",
      "errorMessage": "[GET] \"https://www.atptour.com/en/-/tour/news/latest-filtered-results/0/15\": 403 Forbidden\n",
      "id": "83684289961634816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.atptour.com/en/news/news-filter-results",
      "title": "News",
      "type": "feed",
      "url": "rsshub://atptour/news/en"
    }
  ]
}
```
