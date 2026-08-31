# RescueTime - Release Notes

## Coverage
`index-only`

## Route
- Namespace: `rescuetime`
- Namespace Name: `RescueTime`
- Route Path: `/rescuetime/release-notes/:os?`
- Route Name: `Release Notes`
- Example: `/rescuetime/release-notes`
- URL: `www.rescuetime.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `release-notes.ts`
- Source Module: `_None_`

## Description
| Mac OS | Windows |
| ------ | ------- |
| mac    | windows |

## Parameters
- `os`: OS id, see below


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "| Mac OS | Windows |\n| ------ | ------- |\n| mac    | windows |",
  "example": "/rescuetime/release-notes",
  "heat": 0,
  "location": "release-notes.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Release Notes",
  "parameters": {
    "os": "OS id, see below"
  },
  "path": "/release-notes/:os?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(1) ] to not include 'https://www.rescuetime.com/release-no…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.11/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/app.test.ts:91:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:106:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
