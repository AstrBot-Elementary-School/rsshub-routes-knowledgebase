# Rebase Network - Web3 Geek Daily

## Coverage
`index-only`

## Route
- Namespace: `rebase`
- Namespace Name: `Rebase Network`
- Route Path: `/rebase/geekdaily`
- Route Name: `Web3 Geek Daily`
- Example: `/rebase/geekdaily`
- URL: `rebase.network`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `gaoyifan`
- Source Location: `geekdaily.ts`
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
  - `rebase.network/geekdaily`
- `target`: `/geekdaily`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/rebase/geekdaily",
  "heat": 54,
  "location": "geekdaily.ts",
  "maintainers": [
    "gaoyifan"
  ],
  "name": "Web3 Geek Daily",
  "path": "/geekdaily",
  "radar": [
    {
      "source": [
        "rebase.network/geekdaily"
      ],
      "target": "/geekdaily"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Web3 Geek Daily - Powered by RSSHub",
      "errorAt": "2025-01-14T15:37:22.554Z",
      "errorMessage": "[GET] \"https://db.rebase.network/api/v1/geekdailies?sort=id:desc\": <no response> fetch failed (getaddrinfo ENOTFOUND db.rebase.network)\n",
      "id": "66817557552243712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://rebase.network/geekdaily",
      "title": "Web3 Geek Daily",
      "type": "feed",
      "url": "rsshub://rebase/geekdaily"
    }
  ]
}
```
