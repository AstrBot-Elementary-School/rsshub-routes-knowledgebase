# Outage.Report - Report

## Coverage
`index-only`

## Route
- Namespace: `outagereport`
- Namespace Name: `Outage.Report`
- Route Path: `/outagereport/:name/:count?`
- Route Name: `Report`
- Example: `/outagereport/ubisoft/5`
- URL: `outage.report`
- Language: `_None_`
- Categories: `forecast`
- Maintainers: `cxumol, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Please skip the local service area code for `name`, for example `https://outage.report/us/verizon-wireless` to `verizon-wireless`.

## Parameters
- `name`: Service name, spelling format must be consistent with URL
- `count`: Counting threshold, will only be written in RSS if the number of people who report to stop serving is not less than this number


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
    "forecast"
  ],
  "description": "Please skip the local service area code for `name`, for example `https://outage.report/us/verizon-wireless` to `verizon-wireless`.",
  "example": "/outagereport/ubisoft/5",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "cxumol",
    "nczitzk"
  ],
  "name": "Report",
  "parameters": {
    "count": "Counting threshold, will only be written in RSS if the number of people who report to stop serving is not less than this number",
    "name": "Service name, spelling format must be consistent with URL"
  },
  "path": "/:name/:count?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.11/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
