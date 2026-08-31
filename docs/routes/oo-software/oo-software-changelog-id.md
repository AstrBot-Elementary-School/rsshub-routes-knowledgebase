# O&O Software - Changelog

## Coverage
`index-only`

## Route
- Namespace: `oo-software`
- Namespace Name: `O&O Software`
- Route Path: `/oo-software/changelog/:id`
- Route Name: `Changelog`
- Example: `/oo-software/changelog/shutup10`
- URL: `oo-software.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `changelog.ts`
- Source Module: `_None_`

## Description
| Software        | Id          |
| --------------- | ----------- |
| O\&O ShutUp10++ | shutup10    |
| O\&O AppBuster  | ooappbuster |
| O\&O Lanytix    | oolanytix   |
| O\&O DeskInfo   | oodeskinfo  |

## Parameters
- `id`: Software id, see below, shutup10 by default, can be found in URL


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
  "description": "| Software        | Id          |\n| --------------- | ----------- |\n| O\\&O ShutUp10++ | shutup10    |\n| O\\&O AppBuster  | ooappbuster |\n| O\\&O Lanytix    | oolanytix   |\n| O\\&O DeskInfo   | oodeskinfo  |",
  "example": "/oo-software/changelog/shutup10",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "changelog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Changelog",
  "parameters": {
    "id": "Software id, see below, shutup10 by default, can be found in URL"
  },
  "path": "/changelog/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
