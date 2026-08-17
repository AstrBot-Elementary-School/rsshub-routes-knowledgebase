# Harvard Health Publishing - Health Blog

## Coverage
`index-only`

## Route
- Namespace: `harvard`
- Namespace Name: `Harvard Health Publishing`
- Route Path: `/harvard/health/blog`
- Route Name: `Health Blog`
- Example: `/harvard/health/blog`
- URL: `www.health.harvard.edu/blog`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `health/blog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `www.health.harvard.edu/blog`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/harvard/health/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 213,
  "location": "health/blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Health Blog",
  "parameters": {},
  "path": "/health/blog",
  "radar": [
    {
      "source": [
        "www.health.harvard.edu/blog"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(23) ] to not include 'https://www.health.harvard.edu/blog/r…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.10/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Harvard Health Blog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42585333894603776",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.health.harvard.edu/blog",
      "title": "Harvard Health Blog",
      "type": "feed",
      "url": "rsshub://harvard/health/blog"
    }
  ],
  "url": "www.health.harvard.edu/blog"
}
```
