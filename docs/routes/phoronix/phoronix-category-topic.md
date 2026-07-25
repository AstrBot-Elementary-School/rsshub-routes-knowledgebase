# Phoronix - News & Reviews

## Coverage
`index-only`

## Route
- Namespace: `phoronix`
- Namespace Name: `Phoronix`
- Route Path: `/phoronix/:category?/:topic?`
- Route Name: `News & Reviews`
- Example: `/phoronix/linux/KDE`
- URL: `phoronix.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `oppliate, Rongronggg9`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category
- `topic`: Topic. You may find available parameters from their navigator links. E.g. to subscribe to `https://www.phoronix.com/reviews/Operating+Systems`, fill in the path `/phoronix/reviews/Operating+Systems`


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
  - `phoronix.com/:category?/:topic?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/phoronix/linux/KDE",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 138,
  "location": "index.ts",
  "maintainers": [
    "oppliate",
    "Rongronggg9"
  ],
  "name": "News & Reviews",
  "parameters": {
    "category": "Category",
    "topic": "Topic. You may find available parameters from their navigator links. E.g. to subscribe to `https://www.phoronix.com/reviews/Operating+Systems`, fill in the path `/phoronix/reviews/Operating+Systems`"
  },
  "path": "/:category?/:topic?",
  "radar": [
    {
      "source": [
        "phoronix.com/:category?/:topic?"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Linux Hardware Reviews, Performance Benchmarks & Open-Source / Free Software News - Powered by RSSHub",
      "errorAt": "2026-05-19T22:33:02.755Z",
      "errorMessage": "[GET] \"https://www.phoronix.com/rss.php\": <no response> fetch failed (Request was cancelled.) (Proxy response (503) !== 200 when HTTP Tunneling)\n[GET] \"https://www.phoronix.com/review/linux-72-panther-lake/3\": 403 Forbidden\n",
      "id": "41582925280941056",
      "image": "https://www.phoronix.com/android-chrome-192x192.png",
      "ownerUserId": null,
      "siteUrl": "https://www.phoronix.com/",
      "title": "Phoronix",
      "type": "feed",
      "url": "rsshub://phoronix"
    },
    {
      "description": "Phoronix is the leading technology website for Linux hardware reviews, open-source news, Linux benchmarks, open-source benchmarks, and computer hardware performance tests. - Powered by RSSHub",
      "errorAt": "2025-11-07T00:34:05.198Z",
      "errorMessage": "[GET] \"https://www.phoronix.com/reviews/Operating+Systems\": 403 Forbidden\n",
      "id": "148257239711501312",
      "image": "https://www.phoronix.com/android-chrome-192x192.png",
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "Linux Performance, Benchmarks & Open-Source News - Phoronix",
      "type": "feed",
      "url": "rsshub://phoronix/reviews/Operating%2BSystems"
    }
  ]
}
```
