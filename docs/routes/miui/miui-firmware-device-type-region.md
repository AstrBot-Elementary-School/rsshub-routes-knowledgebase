# MIUI - New firmware

## Coverage
`index-only`

## Route
- Namespace: `miui`
- Namespace Name: `MIUI`
- Route Path: `/miui/firmware/:device/:type?/:region?`
- Route Name: `New firmware`
- Example: `/miui/firmware/aries`
- URL: `miui.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `Indexyz`
- Source Location: `firmware/index.ts`
- Source Module: `_None_`

## Description
| stable  | development |
| ------- | ----------- |
| release | dev         |

| region | region |
| ------ | ------ |
| China  | cn     |
| Global | global |

## Parameters
- `device`: the device `codename` eg. `aries` for Mi 2S
- `type`: type
- `region`: Region, default to `cn`


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
  "description": "| stable  | development |\n| ------- | ----------- |\n| release | dev         |\n\n| region | region |\n| ------ | ------ |\n| China  | cn     |\n| Global | global |",
  "example": "/miui/firmware/aries",
  "heat": 0,
  "location": "firmware/index.ts",
  "maintainers": [
    "Indexyz"
  ],
  "name": "New firmware",
  "parameters": {
    "device": "the device `codename` eg. `aries` for Mi 2S",
    "region": "Region, default to `cn`",
    "type": "type"
  },
  "path": "/firmware/:device/:type?/:region?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
