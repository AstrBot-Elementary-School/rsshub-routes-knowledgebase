# QNAP - Release Notes

## Coverage
`index-only`

## Route
- Namespace: `qnap`
- Namespace Name: `QNAP`
- Route Path: `/qnap/release-notes/:id`
- Route Name: `Release Notes`
- Example: `/qnap/release-notes/qts`
- URL: `www.qnap.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `release-notes.ts`
- Source Module: `_None_`

## Description
| QTS | QuTS hero  | QuTScloud | QSS | QuWAN Orchestrator  | QES | QVP | QuRouter | TAS | AfoBot |
| --- | ---------- | --------- | --- | ------------------- | --- | --- | -------- | --- | ------ |
| qts | quts\_hero | qutscloud | qss | quwan\_orchestrator | qes | qvp | qurouter | tas | afobot |

## Parameters
- `id`: OS id, see below


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
  "description": "| QTS | QuTS hero  | QuTScloud | QSS | QuWAN Orchestrator  | QES | QVP | QuRouter | TAS | AfoBot |\n| --- | ---------- | --------- | --- | ------------------- | --- | --- | -------- | --- | ------ |\n| qts | quts\\_hero | qutscloud | qss | quwan\\_orchestrator | qes | qvp | qurouter | tas | afobot |",
  "example": "/qnap/release-notes/qts",
  "heat": 0,
  "location": "release-notes.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Release Notes",
  "parameters": {
    "id": "OS id, see below"
  },
  "path": "/release-notes/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
