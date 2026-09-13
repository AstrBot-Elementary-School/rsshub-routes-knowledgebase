# Inception Labs - Blog

## Coverage
`index-only`

## Route
- Namespace: `inceptionlabs`
- Namespace Name: `Inception Labs`
- Route Path: `/inceptionlabs/blog`
- Route Name: `Blog`
- Example: `/inceptionlabs/blog`
- URL: `inceptionlabs.ai/blog`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `zdenek-stursa`
- Source Location: `blog.ts`
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
  - `www.inceptionlabs.ai/blog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/inceptionlabs/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "blog.ts",
  "maintainers": [
    "zdenek-stursa"
  ],
  "name": "Blog",
  "path": "/blog",
  "radar": [
    {
      "source": [
        "www.inceptionlabs.ai/blog"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(3) ] to not include 'https://www.inceptionlabs.ai/blog/mer…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "inceptionlabs.ai/blog"
}
```
