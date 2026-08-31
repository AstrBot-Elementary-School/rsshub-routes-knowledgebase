# TokenInsight - Blogs

## Coverage
`index-only`

## Route
- Namespace: `tokeninsight`
- Namespace Name: `TokenInsight`
- Route Path: `/tokeninsight/blog/:lang?`
- Route Name: `Blogs`
- Example: `/tokeninsight/blog/en`
- URL: `tokeninsight.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `fuergaosi233`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
_None_

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
  - `tokeninsight.com/:lang/blogs`
- `target`: `/blog/:lang`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/tokeninsight/blog/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "blog.ts",
  "maintainers": [
    "fuergaosi233"
  ],
  "name": "Blogs",
  "parameters": {
    "lang": "Language, see below, Chinese by default"
  },
  "path": "/blog/:lang?",
  "radar": [
    {
      "source": [
        "tokeninsight.com/:lang/blogs"
      ],
      "target": "/blog/:lang"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-05-26T04:23:55.087Z",
      "errorMessage": "[POST] \"https://www.tokeninsight.com/api/user/search/getAllList\": 403 Forbidden\n",
      "id": "149642094386478103",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://tokeninsight/blog"
    }
  ]
}
```
