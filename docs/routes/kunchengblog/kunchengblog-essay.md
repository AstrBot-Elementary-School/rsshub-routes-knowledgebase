# Kun Cheng - Essay

## Coverage
`index-only`

## Route
- Namespace: `kunchengblog`
- Namespace Name: `Kun Cheng`
- Route Path: `/kunchengblog/essay`
- Route Name: `Essay`
- Example: `/kunchengblog/essay`
- URL: `kunchengblog.com/essay`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `nczitzk`
- Source Location: `essay.ts`
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
  - `kunchengblog.com/essay`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/kunchengblog/essay",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16,
  "location": "essay.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Essay",
  "parameters": {},
  "path": "/essay",
  "radar": [
    {
      "source": [
        "kunchengblog.com/essay"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "This is the blog of K.C. - Powered by RSSHub",
      "errorAt": "2026-06-12T10:02:45.852Z",
      "errorMessage": "[GET] \"https://plausible.io/js/pa-gp2qGRbvWIdmvc_WKuFYr.js.map\": 404 Not Found\n[GET] \"https://plausible.io/js/pa-gp2qGRbvWIdmvc_WKuFYr.js.map\": 404 Not Found\n[GET] \"https://plausible.io/js/pa-gp2qGRbvWIdmvc_WKuFYr.js.map\": 404 Not Found\n",
      "id": "56942077048280065",
      "image": "https://www.kunchengblog.com/architect_icon.png",
      "ownerUserId": null,
      "siteUrl": "https://www.kunchengblog.com/essay",
      "title": "Kun Cheng - Essay",
      "type": "feed",
      "url": "rsshub://kunchengblog/essay"
    }
  ],
  "url": "kunchengblog.com/essay"
}
```
