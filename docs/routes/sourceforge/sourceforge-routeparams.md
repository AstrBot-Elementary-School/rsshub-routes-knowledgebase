# SourceForge - Software

## Coverage
`index-only`

## Route
- Namespace: `sourceforge`
- Namespace Name: `SourceForge`
- Route Path: `/sourceforge/:routeParams?`
- Route Name: `Software`
- Example: `/sourceforge/topic=artificial-intelligence&os=windows`
- URL: `www.sourceforge.net`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `JimenezLi`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
For some URL like <https://sourceforge.net/directory/artificial-intelligence/windows/>, it is equal to [https://sourceforge.net/directory/?topic=artificial-intelligence\&os=windows"](https://sourceforge.net/directory/?topic=artificial-intelligence\&os=windows), thus subscribing to `/sourceforge/topic=artificial-intelligence&os=windows`.

URL params can duplicate, such as `/sourceforge/topic=artificial-intelligence&os=windows&os=linux`.

## Parameters
- `routeParams`: route params, see below


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "For some URL like <https://sourceforge.net/directory/artificial-intelligence/windows/>, it is equal to [https://sourceforge.net/directory/?topic=artificial-intelligence\\&os=windows\"](https://sourceforge.net/directory/?topic=artificial-intelligence\\&os=windows), thus subscribing to `/sourceforge/topic=artificial-intelligence&os=windows`.\n\nURL params can duplicate, such as `/sourceforge/topic=artificial-intelligence&os=windows&os=linux`.",
  "example": "/sourceforge/topic=artificial-intelligence&os=windows",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "name": "Software",
  "parameters": {
    "routeParams": "route params, see below"
  },
  "path": "/:routeParams?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
