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
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:61:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Brave Release Notes | Brave - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
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
