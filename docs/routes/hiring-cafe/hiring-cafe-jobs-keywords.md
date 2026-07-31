# HiringCafe - Jobs

## Coverage
`index-only`

## Route
- Namespace: `hiring.cafe`
- Namespace Name: `HiringCafe`
- Route Path: `/hiring.cafe/jobs/:keywords`
- Route Name: `Jobs`
- Example: `/hiring.cafe/jobs/sustainability`
- URL: `hiring.cafe`
- Language: `_None_`
- Categories: `other`
- Maintainers: `mintyfrankie`
- Source Location: `jobs.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keywords`: Keywords to search for


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
  - `hiring.cafe`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/hiring.cafe/jobs/sustainability",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "jobs.tsx",
  "maintainers": [
    "mintyfrankie"
  ],
  "name": "Jobs",
  "parameters": {
    "keywords": "Keywords to search for"
  },
  "path": "/jobs/:keywords",
  "radar": [
    {
      "source": [
        "hiring.cafe"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Job search results for \"C++\" on HiringCafe - Powered by RSSHub",
      "errorAt": "2025-10-16T18:47:23.809Z",
      "errorMessage": "[POST] \"https://hiring.cafe/api/search-jobs\": 429 Too Many Requests\n",
      "id": "111907108448833536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hiring.cafe/jobs?q=C%2B%2B",
      "title": "HiringCafe Jobs: C++",
      "type": "feed",
      "url": "rsshub://hiring.cafe/jobs/C++"
    },
    {
      "description": "Job search results for \"opengl\" on HiringCafe - Powered by RSSHub",
      "errorAt": "2025-10-16T18:35:35.661Z",
      "errorMessage": "[POST] \"https://hiring.cafe/api/search-jobs\": 429 Too Many Requests\n",
      "id": "111907007229612032",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://hiring.cafe/jobs?q=opengl",
      "title": "HiringCafe Jobs: opengl",
      "type": "feed",
      "url": "rsshub://hiring.cafe/jobs/opengl"
    }
  ]
}
```
