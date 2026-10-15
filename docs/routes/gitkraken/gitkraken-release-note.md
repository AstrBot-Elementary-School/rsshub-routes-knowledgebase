# GitKraken - Release Notes

## Coverage
`index-only`

## Route
- Namespace: `gitkraken`
- Namespace Name: `GitKraken`
- Route Path: `/gitkraken/release-note`
- Route Name: `Release Notes`
- Example: `/gitkraken/release-note`
- URL: `help.gitkraken.com/gitkraken-desktop/current/`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `release-note.ts`
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
  - `help.gitkraken.com/gitkraken-desktop/current/`
### Rule 2
- `source`:
  - `www.gitkraken.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/gitkraken/release-note",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "release-note.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Release Notes",
  "path": "/release-note",
  "radar": [
    {
      "source": [
        "help.gitkraken.com/gitkraken-desktop/current/"
      ]
    },
    {
      "source": [
        "www.gitkraken.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:108:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "This release notes page tracks what’s new and changing in the current version of GitKraken Desktop, including new features, improvements, […] - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "241250520993393664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://help.gitkraken.com/gitkraken-desktop/current/",
      "title": "GitKraken Desktop Release Notes",
      "type": "feed",
      "url": "rsshub://gitkraken/release-note"
    }
  ],
  "url": "help.gitkraken.com/gitkraken-desktop/current/"
}
```
