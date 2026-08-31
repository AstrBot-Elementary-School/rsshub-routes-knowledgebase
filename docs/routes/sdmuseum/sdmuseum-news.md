# Shan Dong Museum - News

## Coverage
`index-only`

## Route
- Namespace: `sdmuseum`
- Namespace Name: `Shan Dong Museum`
- Route Path: `/sdmuseum/news`
- Route Name: `News`
- Example: `/sdmuseum/news`
- URL: `www.sdmuseum.com/`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sdmuseum.com/col/col270324/index.html`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/sdmuseum/news",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "magazian"
  ],
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.sdmuseum.com/col/col270324/index.html"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
