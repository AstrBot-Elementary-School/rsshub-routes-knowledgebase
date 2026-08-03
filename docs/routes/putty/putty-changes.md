# PuTTY - Change Log

## Coverage
`index-only`

## Route
- Namespace: `putty`
- Namespace Name: `PuTTY`
- Route Path: `/putty/changes`
- Route Name: `Change Log`
- Example: `/putty/changes`
- URL: `www.chiark.greenend.org.uk/~sgtatham/putty/changes.html`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `changes.ts`
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
  - `www.chiark.greenend.org.uk/~sgtatham/putty/changes.html`
  - `www.chiark.greenend.org.uk/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/putty/changes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "changes.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Change Log",
  "parameters": {},
  "path": "/changes",
  "radar": [
    {
      "source": [
        "www.chiark.greenend.org.uk/~sgtatham/putty/changes.html",
        "www.chiark.greenend.org.uk/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 328499293065 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:62:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:87:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "PuTTY Change Log - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "89540183534812160",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.chiark.greenend.org.uk/~sgtatham/putty/changes.html",
      "title": "PuTTY Change Log",
      "type": "feed",
      "url": "rsshub://putty/changes"
    }
  ],
  "url": "www.chiark.greenend.org.uk/~sgtatham/putty/changes.html"
}
```
