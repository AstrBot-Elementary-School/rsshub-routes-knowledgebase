# Brave - Release Notes

## Coverage
`index-only`

## Route
- Namespace: `brave`
- Namespace Name: `Brave`
- Route Path: `/brave/latest`
- Route Name: `Release Notes`
- Example: `/brave/latest`
- URL: `brave.com/latest`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `latest.ts`
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
  - `brave.com/latest`
  - `brave.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/brave/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15,
  "location": "latest.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Release Notes",
  "parameters": {},
  "path": "/latest",
  "radar": [
    {
      "source": [
        "brave.com/latest",
        "brave.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Brave Release Notes | Brave - Powered by RSSHub",
      "errorAt": "2026-08-27T06:55:52.989Z",
      "errorMessage": "Cannot read properties of null (reading '1')\n",
      "id": "74302476579862528",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://brave.com/latest",
      "title": "Brave Release Notes | Brave",
      "type": "feed",
      "url": "rsshub://brave/latest"
    }
  ],
  "url": "brave.com/latest"
}
```
